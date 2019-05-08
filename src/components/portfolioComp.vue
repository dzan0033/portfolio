<template>
  <v-container id="sectionThree">
    <v-layout>
      <v-flex>
        <!--<h4>Transition:</h4>
        <v-btn dark color="primary" v-on:click="showOne = !showOne">
          Toggle
        </v-btn>
        <p v-if="showOne">hello</p>
        <hr class="mb-2"> -->  
        
        <div id="box">
          <v-layout align-end justify-end column>
          <v-flex>
          <img id="portfolio" src="../assets/img/portfolio.png" align="center">
          </v-flex>
          </v-layout>
        </div>
          
        

        <v-layout row wrap>
          <v-flex xs12 sm6 md12s offset-sm3>
            <v-card>
              <v-img
                class="white--text"
                height="200px"
                :src="require('../assets/img/photo.jpg')"
              >
                <v-container fill-height fluid>
                  <v-layout fill-height>
                    <v-flex xs12 align-end flexbox>
                      <span class="headline">Top 10 Australian beaches</span>
                    </v-flex>
                  </v-layout>
                </v-container>
              </v-img>
            </v-card>
          </v-flex>
        

        
            <v-flex xs12 sm6 offset-sm3>
              <v-card>
                <v-img
                  class="white--text"
                  height="200px"
                  src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                >
                  <v-container fill-height fluid>
                    <v-layout fill-height>
                      <v-flex xs12 align-end flexbox>
                        <span class="headline">Top 10 Australian beaches</span>
                      </v-flex>
                    </v-layout>
                  </v-container>
                </v-img>
              </v-card>
            </v-flex>
         
            <v-flex xs12 sm6 offset-sm3>
              <v-card>
                <v-img
                  class="white--text"
                  height="200px"
                  src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                >
                  <v-container fill-height fluid>
                    <v-layout fill-height>
                      <v-flex xs12 align-end flexbox>
                        <span class="headline">Top 10 Australian beaches</span>
                      </v-flex>
                    </v-layout>
                  </v-container>
                </v-img>
              </v-card>
            </v-flex>

            <v-flex xs12 sm6 offset-sm3>
              <v-card>
                <v-img
                  class="white--text"
                  height="200px"
                  src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                >
                  <v-container fill-height fluid>
                    <v-layout fill-height>
                      <v-flex xs12 align-end flexbox>
                        <span class="headline">Top 10 Australian beaches</span>
                      </v-flex>
                    </v-layout>
                  </v-container>
                </v-img>
              </v-card>
            </v-flex>

            <v-flex xs12 sm6 offset-sm3>
              <v-card>
                <v-img
                  class="white--text"
                  height="200px"
                  src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                >
                  <v-container fill-height fluid>
                    <v-layout fill-height>
                      <v-flex xs12 align-end flexbox>
                        <span class="headline">Top 10 Australian beaches</span>
                      </v-flex>
                    </v-layout>
                  </v-container>
                </v-img>
              </v-card>
            </v-flex>

          </v-layout>


        <div id="box">
          <v-layout align-start justify-start column>
          <v-flex id="line">
            <img id="line" src="../assets/img/line.png" align="center">
          </v-flex>
          </v-layout>
        </div>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
   export default {
    data: () => ({
      cards: [
        { title: 'Pre-fab homes', src: 'https://cdn.vuetifyjs.com/images/cards/house.jpg', flex: 12 },
        { title: 'Favorite road trips', src: 'https://cdn.vuetifyjs.com/images/cards/road.jpg', flex: 6 },
        { title: 'Best airlines', src: 'https://cdn.vuetifyjs.com/images/cards/plane.jpg', flex: 6 }
      ]
    })
  }
</script>

<style lang="scss" scoped>
  #sectionThree{
    max-width: 110% !important; 
  }
  
#box{
  height: 200px;
  width: auto;
  background-color: #D7CCC4;
}

#portfolio{
  height: 160px;
}

#line{
  height: 200px;
}

@media (min-width: 600px){
.flex.offset-sm3 {
    margin-left: 0;
}
}
</style>