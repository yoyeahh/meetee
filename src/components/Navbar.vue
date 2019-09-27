<template>
  <nav>
    <v-app-bar app class="white" :flat="false">
      <v-row align="center" justify="start">
        <!-- <v-col md="1"> </v-col> -->
        <v-html>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</v-html>
        <v-col>
          <v-img
            src="../assets/meetee-logo.png"
            max-width="60"
            max-height="60"
          ></v-img>
        </v-col>
        <v-html>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; </v-html>
        <v-col>
          <v-btn
            rounded
            v-for="link in links"
            :key="link"
            color="blue-gray"
            text
            class="my-2"
            >{{ link }}
          </v-btn>
        </v-col>
      </v-row>
    </v-app-bar>
  </nav>
</template>

<script>
export default {
  name: "navbar",
  data: () => ({
    links: ["About Us", "Services", "Contact Us", "sign-up", "log-in"]
  })
};
</script>
