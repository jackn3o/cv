<template>
  <v-app>
    <v-content>
      <Main />
    </v-content>
  </v-app>
</template>

<script>
import Main from "./components/Main.vue";

export default {
  name: "App",

  components: {
    Main
  },

  data: () => ({
    //
  })
};
</script>

<style lang="scss">
body {
  .theme--light.v-application {
    background-color: #f0f0f6;
    color: #5f6f81;
    background-image: url(./assets/triangles-top.svg),
      url(./assets/triangles-bottom.svg);
    background-position: left top, right bottom;
    background-repeat: no-repeat;
    background-size: inherit;
  }
}
</style>