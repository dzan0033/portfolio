<template>
  <v-container id="sectionTwo">
    <v-layout justify-center row> 
      <v-flex  justify-center row>

    <v-layout align-center justify-center column fill-height> 
        <h2 class="om">Om</h2>
        <h2 class="mig">mig</h2>
        <img id="photo" src="../assets/img/photo.jpg">
    </v-layout>
      </v-flex>

      <v-flex id="beskrivelse">
          <div class="beskriv1">
          Jeg er multimediedesign studerende med en stor passion for grafisk 
          design og digital kommunikation. Jeg har fokus på front-end kodning og 
          konceptudvikling. Jeg designer og leverer visual branding og rebranding. 
          Samtidig tilbyder jeg design af website, SoMe content og pakkeløsninger 
          til print materiale, samt andet online PR materiale. </div>
          
          <div class="beskriv1">
          Min kærlighed for design og det kreative driver min vilje til at skabe 
          de bedste resultater og videreudvikle mine kompetencer. Jeg har i mange 
          år arbejdet i en branche hvor den visuelle præsentation har haft en stor 
          påvirkning virksomheden vækst, og derfor ved jeg hvad der skal til for 
          at fange brugerens opmærksomhed og levere de bedste resultater. </div>

          <v-layout align-end justify-end column>
              <v-flex>
              <img id="sign" src="../assets/img/sign.png"/>
              </v-flex>
          </v-layout>
          

          <v-layout align-center justify-center>
          <v-flex ml-5>
            <div class="text-xs-center">
    <v-dialog
      v-model="dialog"
      width="500"
    >
      <template v-slot:activator="{ on }">
        <p
          
          v-on="on"
        >
               <img id="button" src="../assets/img/knap.png"/>
        </p>
      </template>

      <v-card>
        <v-card-title
          class="headline grey lighten-2"
          primary-title
        >
          Privacy Policy
        </v-card-title>

        <v-card-text>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </v-card-text>

        <v-divider></v-divider>

        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn
            color="primary"
            flat
            @click="dialog = false"
          >
            I accept
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
            
          </v-flex>
          
          
          
          
          <v-flex mr-5>
             <div class="text-xs-center">
    <v-dialog
      v-model="dialog"
      width="500"
    >
      <template v-slot:activator="{ on }">
        <p
          
          v-on="on"
        >
               <img id="button" src="../assets/img/knap.png"/>
        </p>
      </template>

      <v-card>
        <v-card-title
          class="headline grey lighten-2"
          primary-title
        >
          Privacy Policy
        </v-card-title>

        <v-card-text>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </v-card-text>

        <v-divider></v-divider>

        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn
            color="primary"
            flat
            @click="dialog = false"
          >
            I accept
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
          </v-flex>
          </v-layout>  
      </v-flex>

    </v-layout>
  </v-container>
</template>

<script>
  export default {
    data() {
      return {
        show: true
      }
    },
    methods: {
  
    }
  }
</script>

<style lang="scss" scoped>
#sectionTwo {
  height: 100vh
}
#photo{
  height: 400px;
  width: auto;
  border-radius: 30px;
  align-items: center;
}
#border{
  height: 400px;
  width: 290px;
  border: 4px solid #C3B1A6;
  border-radius: 30px;
}

.beskriv1{
  height: 100px;
  width: 400px;
  padding: 0px;
  margin: 60px;
  color: #C3B1A6;
}

#button{
  height: 70px;
}

.om{
  color: #C3B1A6;
  font-size: 90px;
  font-family: 'News Cycle', sans-serif;
  line-height: 0.2;
  margin-right: 270px;
  margin-left: 120px;
}

.mig{
  color: #C3B1A6;
  font-size: 90px;
  font-family: 'News Cycle', sans-serif;
  margin-left: 120px;
}

#sign{
  height: 60px;
  margin-right: 120px;
}
</style>

