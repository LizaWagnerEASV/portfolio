<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span></span>
        <img id="logo" :src="require('./assets/logo1.png')">
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <span class="font-weight-light"></span>
      <v-spacer></v-spacer>

      <h4></h4>
      <v-btn flat href="#about">Om mig</v-btn>
      <v-btn flat href="#portfolio">Portfolio</v-btn>
      <v-btn flat href="#contact">Contact</v-btn>
    </v-toolbar>

    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "App",
  components: {},
  data() {
    return {
      //
    };
  }
};
</script>


<style lang="scss" scoped>
#logo {
  width: 85px;
  height: 50px;
}
</style>