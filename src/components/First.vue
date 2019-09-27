<template>
  <v-container>
    <div id="landing-page">
      <div class="home">
        <!-- <h1 class="purple lighten-3 white--text text--darken-1">test vue</h1>
      <h2 class="display-3">test test</h2>

      <v-btn>
        <v-icon>mdi-anchor</v-icon>
        click
        </v-btn>-->

        <v-row>
          <v-col>
            <v-html>
              <p>&nbsp;</p>
              <p>&nbsp;</p>
            </v-html>
            <p class="display-3 font-weight-bold pink--text text--darken-1">
              <v-html>&nbsp;</v-html> M e e t e e
            </p>
            <p class="display-1 font-weight-thin pink--text">
              <v-html>&nbsp; &nbsp;</v-html> R E S E R V A T I O N
            </p>
            <blockquote class="blockquote">
              Meetee Reservation System is Lorem ipsum dolor sit amet,
              consectetur adipisicing elit. Harum maiores modi quidem veniam,
              expedita quis laboriosam, ullam facere adipisci, iusto, voluptate
              sapiente corrupti asperiores rem nemo numquam fuga ab at.
            </blockquote>
            <v-html>&nbsp; &nbsp; </v-html>
            <v-btn large rounded color="pink" dark>LEARN MORE</v-btn>
          </v-col>
          <v-col>
            <v-img
              src="../assets/meeteefinal.png"
              max-width="750"
              max-height="550"
            ></v-img>
          </v-col>
        </v-row>

        <v-row> </v-row>
      </div>
    </div>
  </v-container>
</template>

<script>
export default {
  data: () => {}
};
</script>

<style>
#landing-page {
  background-color: #fff;
  background-size: cover;
  position: relative;
}
</style>
