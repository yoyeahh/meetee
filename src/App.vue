<template>
  <v-app>
    <Navbar />
    <v-content>
      <First />
      <RoomPresent />
      <Room />` `
    </v-content>
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
import First from "./components/First";
import RoomPresent from "./components/RoomPresent";
import Room from "./components/Room";

export default {
  name: "App",
  components: {
    Navbar,
    First,
    RoomPresent,
    Room
  },

  data: () => ({
    //
  })
};
</script>
<style>
#app {
  background-color: #ffffff;
  background-size: cover;
  position: relative;
}
</style>
