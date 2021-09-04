<template>
  <v-app>
    <v-app-bar app color="primary" dark height="64">
      <v-toolbar-title>Samsung KPI Team</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn text @click="gotoHome">HOME</v-btn>
      <v-btn text @click="gotoAbout">STATISTICS</v-btn>
    </v-app-bar>
    <v-main>
      <!-- <HelloWorld/> -->
    </v-main>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';

export default {
  name: "App",
  methods: {
    gotoHome() {
      this.$router.push({ name: "home" });
    },
    gotoAbout() {
      this.$router.push({ name: "about" });
    },
  },
  components: {
    // HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
