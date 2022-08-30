<script>
</script>
<template> 
  <v-app>
  <v-container class="placeholder">
    <div class="navbar" style="display:flex">
      <v-card style="border-radius: 0px">
        <v-navigation-drawer
          permanent
          expand-on-hover
        > 
          <div class="barsize0">
          <v-image   class="iflogo transition-fast-in-fast-out" >
            
          </v-image>
          </div>
          <v-divider></v-divider>
          <div class="barsize1">
            <v-list-item>
              <v-list-item-icon>
                <v-icon>mdi-folder</v-icon>
              </v-list-item-icon>
              <v-list-item-title>  </v-list-item-title>
            </v-list-item>
          </div>
          <v-divider></v-divider>
          <div class="barsize2">
          <v-list
            nav
            dense
          >
            <v-list-item>
              <v-list-item-icon>
                <v-icon>mdi-folder</v-icon>
              </v-list-item-icon>
              <v-list-item-title>  </v-list-item-title>
            </v-list-item>
          </v-list>
          </div>
          <v-divider></v-divider>
          <div class="barsize3">
            <v-list-item>
              <v-list-item-icon>
                <v-icon>mdi-folder</v-icon>
              </v-list-item-icon>
              <v-list-item-title>  </v-list-item-title>
            </v-list-item>
          </div>
        </v-navigation-drawer>
      </v-card>
    </div>
    <div  class="appbar-cont">
      <v-app-bar
        style="height:15%"
        id="appbar"
      >  
        <v-toolbar-title>TITLE</v-toolbar-title> 
        <v-spacer></v-spacer>
        <v-menu
        >
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
    max-width: 13vw;
    position: relative;
}
.appbar-cont{
  display: flex;
  width: 100%;
}
#appbar{
  background-color: #6E9EB2;
  border-left: white 1px solid;
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
</style>