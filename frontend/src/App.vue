<template>
  <v-app>
    <v-app-bar app color="primary" dark height="64">
      <v-toolbar-title>Samsung KPI Team</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn text @click="gotoCpuLoadProfiler">CpuLoad/Memory</v-btn>
      <v-btn text>Statistics</v-btn>
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
    gotoCpuLoadProfiler() {},
  },
  components: {
    // HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
