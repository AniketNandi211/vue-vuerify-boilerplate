<template>
  <v-container class="grey lighten-5">
    <v-row no-gutters class="mb-3">
      <v-col align-self="center">
        <v-btn color="success" outlined>text</v-btn>
      </v-col>
      <v-col>
        <v-btn color="cyan" flat dark>text</v-btn>
      </v-col>
      <v-col>
        <v-btn outlined color="purple" dark>text</v-btn>
      </v-col>
    </v-row>

    <v-row no-gutters>
      <v-col>
        <v-btn icon color="green">
          <v-icon>mdi-flower-tulip-outline</v-icon>
        </v-btn>
      </v-col>
      <v-col>
        <v-btn color="green" outlined>
          <span>Done</span>
          <v-icon right>mdi-check</v-icon>
        </v-btn>
      </v-col>
      <v-col>
        <v-btn depressed dark color="green">
          <v-icon left>mdi-alpha-f-circle-outline</v-icon>
          <span>Fuck</span>
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.cont {
  height: 1200px;
}
</style>>
