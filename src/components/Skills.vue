<template>
  <div class="skills">
  <v-container fluid>
    <v-row align="center" class="skills-title py-5" style="background-color: #f8f5e9; text-align: center">
      <v-col md="5">
        <v-divider style="border-color: #3e2723; border-width: 1px;"></v-divider>
      </v-col>
      <v-col md="2" style="color: #3e2723;">
      <h1>Skills</h1>
      <h6>ー 経験技術 ー</h6>
      </v-col>
      <v-col md="5">
        <v-divider style="border-color: #3e2723; border-width: 1px;"></v-divider>
      </v-col>
      <v-col> </v-col>
    <!-- <v-col cols="12" xs="2" sm="3" md="4" lg="4" v-for="(skill, index) in skills" :key="index">
    <v-card>
    <v-img 
    :src="skills.icon" 
    style="cursor: pointer;">
    </v-img>
    </v-card>
    </v-col> -->
    </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data: () => ({
    skills: [{icon: "src/assets/SkillLogo/HTML5.png"}]
  })
};
</script>

<style>
</style>