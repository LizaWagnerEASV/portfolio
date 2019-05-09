<template>
  <v-container>
    <v-layout>
      <v-flex>
        <h2 class="black--text mb-4" id="portfolio">PORTFOLIO</h2>
      </v-flex>
    </v-layout>
    <v-layout row wrap>
      <v-flex xs12 md4>
        <v-card>
          <img id="pint" src="../assets/DSC_0280-Recovered-paint.png" height="300px"></v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Photoshop cartoon effect</div>

              <span class="grey--text"></span>
            </div>
          </v-card-title>

          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn icon @click="show = !show">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text v-show="show">Cartoon effect har lavet vha vector art in Photoshop, ifølge tutorial: https://www.youtube.com/watch?v=VuQhhg_y22E&t=193s</v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
      <v-flex xs12 md4>
        <v-card>
          <img id="unimg" src="../assets/uniton-logo.svg"></v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Uniton logotype</div>
              <span class="grey--text"></span>
            </div>
          </v-card-title>

          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn icon @click="show1 = !show1">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text
              v-show="show1"
            >Denne logo kan muligvis bruges til en firma med første prioriteten som enhed, venskab og ligestilling. Inspirationen kommer fra de olimpiske ringe. Forskellige farve bruges til at vise enhed, uafhængig af køn, baggrund eller religion. Et blomst symboliserer liv og håb.</v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
      <v-flex xs12 md4>
        <v-card>
          <img id="insta" src="../assets/pexels-photo-1955134.png" height="300px"></v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">3D pop out photo</div>
              <span class="grey--text"></span>
            </div>
          </v-card-title>

          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn icon @click="show2= !show2">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text
              v-show="show2"
            > 3D pop up Photoshop tutorial, ifølge video https://www.youtube.com/watch?v=L02PGQGr3VQ
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
      <v-flex xs12 md4>
        <v-card>
          <img id="fantasy" src="../assets/pexels-photo-1972243.png" height="300px"></v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Fantasy frame</div>
              <span class="grey--text"></span>
            </div>
          </v-card-title>

          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn icon @click="show3 = !show3">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text
              v-show="show3"
            >Photoshop tutorial fra 
            https://www.youtube.com/watch?v=32pOT1TI6JM&t=6s
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
      <v-flex xs12 md4>
        <v-card>
          <img id="life" src="../assets/LIFE-Liza-MMDda.png" height="300px"></v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Life</div>
              <span class="grey--text"></span>
            </div>
          </v-card-title>

          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn icon @click="show4 = !show4">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text
              v-show="show4"
            >Denne billede fik den anden plads i fotokonkurrense i multimediedesignklassen. Billede indeholder minimal redigering i Photoshop, som var en karv til konkurrence</v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
      <v-flex xs12 md4>
        <v-card>
          <img id="moon" src="../assets/moonlight.png" height="300px"></v-img>

          <v-card-title primary-title>
            <div>
              <div class="headline">Moonlight</div>
              <span class="grey--text"></span>
            </div>
          </v-card-title>

          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn icon @click="show5 = !show5">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>

          <v-slide-y-transition>
            <v-card-text
              v-show="show5"
            >Vector illustartion, lavet ifølge tutorial
            https://www.youtube.com/watch?v=RtnCn65MdN0&t=125s
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>

      <v-img src="../assets/pexels-photo-1972243.png" height="300px"></v-img>
    </v-layout>

<hr>


 <v-layout fluid>
      <h2 class="black--text mb-5" id="contact">CONTACT</h2>
    </v-layout>
     <img id="visit" src="../assets/visitkort2-contact.svg" height="300px" />


 

    

   

    

 


    </v-layout>
  </v-container>
</template>







<script>
export default {
  data() {
    return {
      show: false,
      show1: false,
      show2: false,
      show3:false,
      show4: false,
      show5: false,

    };
  },
  methods: {}
};
</script>

<style lang="scss" scoped>



#contact {
  margin: 30px auto 0;
}
#pint {
  width: 350px;
  height: 5%;
  
}

#unimg {
  width:370px;
  height: 5%;
}

#insta {
  width: 350px;
  height: 5%;
}

#fantasy {
   width: 350px;
 }
 
#life {
  width: 350px; 
}

 #moon {
width:350px;
 }

</style>


