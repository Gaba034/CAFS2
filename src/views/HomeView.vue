<template>
  <v-app  style="background-color:#1D6382" view="lHh Lpr lFf">
    <v-app-bar
    flat
    outlined
    color="#1D6382"
    >
    <div class="btn-container">
      <div id="app">
        <nav>
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About</router-link>
        </nav>
        <router-view/>
      </div>
      <div >
        <v-btn class="v-btn btn-text">
         Cadastro
        </v-btn>
      </div>
      <v-divider 
      dark
      vertical
      inset
      class="mx-4"
      >
      </v-divider>
      <div>
        <v-btn class="v-btn">
         Login
        </v-btn>
      </div>
    </div>
      <div class="spheres"
      >
        <div class="sphere"></div>
        <div class="sphere"></div>
        <div class="sphere">
          <div class="image"></div>
        </div>
        <div class="sphere"></div>
        <div class="sphere"></div>
        <div class="sphere"></div>

      </div>
    </v-app-bar>
    <v-container>
      <div 
      style="
      background-color:#1D6382;
      padding-top:10%;
  

      "
      class="text-container "
      >
      <div class="sphere-cube"></div>
      <div class="cube"></div>
      <div class="cube">
        <div class="image1"></div>
      </div>
      <div class="text">
        <div class="text text-shadow">
          Controle de Acesso a Fábrica de Software
        </div>
        <div class="text text-shadow">
          O Controle de acesso 
          à fábrica de software, 
          referido pelo acrônimo C.A.F.S, 
          é um sistema que busca auxiliar 
          os coordenadores e as suas equipes
          a gerenciarem a sua jornada de trabalho 
          previamente estabelecida
        </div>
      </div>
    </div>
    </v-container>
  </v-app>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
  }
}
</script>
