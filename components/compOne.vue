<template>
  <v-container>
    <v-layout>
      <v-flex>
        <img
          style="object-fit: cover; max-width;100%;"
          id="coverimg"
          src="../assets/liza-cover.png"
          alt
        >

        <h2 class="black--text mb-4"  id="about">OM MIG</h2>
        <p></p>
      </v-flex>
    </v-layout>
    <v-layout>
      <v-flex>
        <div class="text-xs-center" style="margin-left:420px; width:100px">
          <v-dialog v-model="dialog" width="560">
            <template v-slot:activator="{ on }">
              <v-btn color="#e6e6e6" v-on="on">Video CV</v-btn>
            </template>

            <v-card>
              <iframe
                width="560"
                height="315"
                 src="https://www.youtube.com/embed/K9vTh8CH068" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
              ></iframe>
            </v-card>
          </v-dialog>
        </div>
      </v-flex>
      <v-flex>
        <div class="text-xs-center" style="width:100px; margin-right:400px">
          <v-dialog v-model="dialog2" width="500">
            <template v-slot:activator="{ on }">
              <v-btn color="#e6e6e6" v-on="on">CV</v-btn>
            </template>

            <v-card>
              <img id="cvimg" src="../assets/CV.svg" alt>
              <v-divider></v-divider>

              <v-card-actions>
                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
          </v-dialog>
        </div>
      </v-flex>
    </v-layout>

    <hr>
  </v-container>
</template>




<script>
export default {
  data() {
    return {
      showOne: true,
      showTwo: true,
      showThree: true,
      dialog: false,
      dialog2: false
    };
  }
};
</script>

<style lang="scss" scoped>
#cvimg {
  width: 500px;
}
#coverimg {
  margin-left: -15%;

  height: 100vh;
}
</style>
