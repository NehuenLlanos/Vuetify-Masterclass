<template>
  <!--
  Route component que utlizamos en el vuetify
  Todos los componentes que usemos de vuetify tienen que estar dentro de aca.
  Seria como un mounting point para todos los componentes
  -->
  <v-app>
<!--
    Cada componente de vuetify renderiza su propio html que nosotros no sabemos como es
    porque no nos interesa pero sabemos que hace algo yendo a la página con todos los componentes
    -->
<!--
    Podemos colocarle un monton de propiedades a la app-bar que tenemos que ir viendo en la cartilla
    de vuetify,
    -->

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
