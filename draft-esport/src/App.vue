<template>
  <v-app>
    <body>
      <v-container-fluid> 
        <v-section class="gauche">
          <ButtonCS/>
        </v-section>
        <v-section class="home-img">
          <div class="bloc-logo">
            <v-img class="logo" src="./assets/ctr-logo.png"></v-img>
          </div>
          <div class="bloc-kart">
            <v-img class="kart" src="./assets/kart.png"></v-img>
          </div>
          <div class="btn">
            <Button/>
          </div>
        </v-section>
        <v-section class="gauchebas">
          <Identification/> <ButtonJoin/>
        </v-section>
      </v-container-fluid> 
    </body>
  </v-app>
</template>

<script>
import Button from './components/Button';
import ButtonCS from './components/ButtonCS';
import ButtonJoin from './components/ButtonJoin';
import Identification from './components/Identification';

export default {
  name: 'App',

  components: {
    Button,
    ButtonCS,
    ButtonJoin,
    Identification
  },

  data: () => ({
    //
  }),
};
</script>

<style>

body{
  background-image: url("./assets/bgHome.jpg");
  height: 100vh;

}

.home-img{
  float: right;
  width: 55%;
}

.bloc-logo{
  width: 500px;
  position: absolute;
}

.bloc-kart{
  width: 500px;
  margin-top: 24%;
  position: absolute;
}

.btn{
  margin-top: 82%;
}

.gauche{
  float: left;
  margin-top: 20%;
  margin-left: 5%;
}

.gauchebas{
  float: left;
  margin-top: 10%;
  margin-left: 5%;
}



</style>
