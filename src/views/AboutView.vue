<template>
  <v-app>
  <v-container class="placeholder">
    <div class="navbar" style="display:flex">
      <v-card >
        <v-navigation-drawer
          permanent
          expand-on-hover
        > 
          <div class="barsize0">
          <v-image   class="iflogo transition-fast-in-fast-out" >
            
          </v-image>
          </div>
          <v-divider></v-divider>
          <div class="barsize1">NOMES</div>
          <v-divider></v-divider>
          <div class="barsize2">
          <v-list
            nav
            dense
          >
            <v-list-item link>
              <v-list-item-icon>
                <v-icon>mdi-folder</v-icon>
              </v-list-item-icon>
              <v-list-item-title>My Files</v-list-item-title>
            </v-list-item>
            <v-list-item link>
              <v-list-item-icon>
                <v-icon>mdi-account-multiple</v-icon>
              </v-list-item-icon>
              <v-list-item-title>Shared with me</v-list-item-title>
            </v-list-item>
            <v-list-item link>
              <v-list-item-icon>
                <v-icon>mdi-star</v-icon>
              </v-list-item-icon>
              <v-list-item-title>Starred</v-list-item-title>
            </v-list-item>
          </v-list>
          </div>
          <v-divider></v-divider>
          <div class="barsize3">OUTROS LINKS</div>
        </v-navigation-drawer>
      </v-card>
    </div>
    <div class="appbar">
      <v-app-bar
        dark
        style="height:15%"
      >
        <v-app-bar-nav-icon></v-app-bar-nav-icon>
  
        <v-toolbar-title>Page title</v-toolbar-title>
  
        <v-spacer></v-spacer>
  
        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>
  
        <v-btn icon>
          <v-icon>mdi-magnify</v-icon>
        </v-btn>
  
        <v-menu
          left
          bottom
        >
          <template v-slot:activator="{ on, attrs }">
            <v-btn
              icon
              v-bind="attrs"
              v-on="on"
            >
              <v-icon>mdi-dots-vertical</v-icon>
            </v-btn>
          </template>
  
          <v-list>
            <v-list-item
              v-for="n in 5"
              :key="n"
              @click="() => {}"
            >
              <v-list-item-title>Option {{ n }}</v-list-item-title>
            </v-list-item>
          </v-list>
        </v-menu>
      </v-app-bar>
    </div>
  </v-container>
</v-app>
</template>
<style>
@media (min-width: 1000px)
{.container {
    max-width: 100%;
}}
.v-navigation-drawer__content {
  overflow-y:visible;
  overflow-x: visible;
}
.placeholder{
  display: flex;
  padding: 0;
  margin: 0;
  height: 100%;
  width: 100%;
}
.navbar{
    height: 100%;
    width: auto;
    max-width: 15vw;
    position: relative;
}
.appbar{
  display: flex;
  width: 100%;
}
.navbar:hover .iflogo{
  height: auto;
  width: 50%;
  background-image: url(@/assets/AB.jpg);
  background-size: 100% 100%;
}
.barsize0{
  background-color: #6E9EB2;
  min-height: 15%;
  max-height: 20%;
  display: flex;
  justify-content: center;
}
.barsize1{
  background-color: #6E9EB2;
  min-height: 20%;
  height: auto;
  max-height: 20%;
}
.barsize2{
  background-color: #6E9EB2;
  min-height: 50%;
  height: auto;
  max-height: 60%;
}
.barsize3{
  background-color:#6E9EB2 ;
  min-height: 30%;
  height: auto;
  max-height:100%;
}
.iflogo{
  height: auto;
  width: 100%;
  background-image: url(@/assets/AB.jpg);
  background-size: 100% 100%;
}
</style>