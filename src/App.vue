<template>
  <v-app>
    <v-app-bar app
      style="background-color: rgb(255, 138, 27)"
      dark>
      <v-container fluid>
        <v-row>
          <v-col lg="5">
            <v-img alt="ASEG Logo" class="shrink mr-2" contain src="../public/logo-blanco.png" transition="scale-transition"
          width="50" />
          </v-col>
          <v-col lg="7">
            <span style="font-size: 1.7rem">DATASEG</span>

          </v-col>
        </v-row>
      </v-container>
      <v-spacer></v-spacer>
    </v-app-bar>

    <v-main>
      <DataTon />
      <!-- <HelloWorld/> -->
    </v-main>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
import DataTon from './components/DataTon.vue';

export default {
  name: 'App',

  components: {
    // HelloWorld,
    DataTon,
  },

  data: () => ({
    //
  }),
};
</script>
