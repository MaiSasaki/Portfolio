<template>
  <v-app>
    <v-app-bar color="#3a6ba5" dark app>
      <v-toolbar-title class="font-weight-bold">PORTFOLIO</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="d-md-flex">
        <v-btn text>HOME</v-btn>
        <v-divider inset vertical></v-divider>
        <v-btn text>ABOUT</v-btn>
        <v-divider inset vertical></v-divider>
        <v-btn text>CONTACT</v-btn>
      </v-toolbar-items>
    </v-app-bar>
    <v-main>
      <Top />
    </v-main>
    <v-footer color="#3a6ba5" dark app class="font-weight-bold"
      >@Mai Sasaki</v-footer
    >
  </v-app>
</template>

<script>
import Top from "./components/Top";

export default {
  name: "App",

  components: {
    Top,
  },

  data: () => ({
    //
  }),
};
</script>
