<template>
  <v-app>
    <v-app-bar app color="teal" dark dense>
      <v-icon dark class="mr-2">mdi-volleyball</v-icon>
      <span class="font-weight-bold">Vuetify Setup</span>
      <v-spacer></v-spacer>
      <v-btn :ripple="true" flat icon>
        <v-icon>mdi-instagram</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",

  components: {
    HelloWorld,
  },

  data: () => ({
    collapseOnScroll: true,
  }),
};
</script>
