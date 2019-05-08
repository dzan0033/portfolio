<template>
    <div id="sectionSix">
        <v-layout align-center justify-center row wrap>  
            <v-layout justify-end >
            <v-flex md6 order-md1>
                <img id="logoimgimg" src="../assets/DBlogo.png"/>
            </v-flex> 
            </v-layout>
            <v-flex md6 order-md2>     
                <div id="infoboxtext">
                  <p>  <v-icon dark>home</v-icon> Home</p>

                    <p>  <v-icon>info</v-icon> info</p>
                </div>
            </v-flex> 
        </v-layout>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

#sectionSix {
  background-color: #D7CCC4;

}
#logoimgimg{
    height: 200px;
    margin: 60px 0 40px 0;
}

#infobox{
    height: 250px;
    margin: 40px 0 0 0;
}
#infoboxtext {
    padding:40px;
    background-image: url('../assets/img/business.png');
    height:250px;
    background-size: contain;
    background-repeat: no-repeat
}
</style>