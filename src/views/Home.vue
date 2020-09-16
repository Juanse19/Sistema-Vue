<template>
  <v-container fluid>
    <v-slide-y-transition mode="out-in">
      <v-layout column align-center>
        <img src="https://www.nubetecnologica.com/wp-content/uploads/2017/12/matec-logo.jpg" alt="MATEC" class="mb-5">
        <blockquote>
          
          
              <div class="home">
                 <navigation/>
                  <h1>Bienvenidos</h1>
                  <p v-if="userLogged">User loggued: {{userLogged}}</p>
                 </div>

          
        </blockquote>
      </v-layout>
    </v-slide-y-transition>
  </v-container>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<script>



</script>
