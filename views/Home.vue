<template>
  <v-container grid-list-md text-xs-center>
    <v-layout row wrap>
      <v-flex xs12 class="blue--text text--accent-2">
        <comp-one/>
        <comp-two/>
        <comp-three/>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import compOne from "@/components/compOne.vue";
import compTwo from "@/components/compTwo.vue";
import compThree from "@/components/compThree.vue";

export default {
  name: "home",
  data() {
    return {
      show: false
    };
  },
  components: {
    compOne,
    compTwo,
    compThree
  }
};
</script>
<style lang="scss">
</style>


