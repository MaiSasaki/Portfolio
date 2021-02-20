<template>
  <div class="about">
    <div class="py-5" style="background-color: #f8f5e9; text-align: center">
    <h1>
      About
    </h1>
    <h6>
      ー 私について ー
    </h6>
    </div>
    <v-container fluid>
      <v-row justify="center" class="pa-0" style="background-color: #f8f5e9">
        <v-col md="3">
          <Profile />
        </v-col>
        <v-col md="6" class="pl-15">
          <Career />
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
import Profile from "./Profile";
import Career from "./Career";

export default {
  components: {
    Profile,
    Career,
  },
};
</script>

<style>
.about {
  color: #3e2723;
}
</style>