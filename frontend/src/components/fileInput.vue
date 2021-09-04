<template>
  <div id="fileInput">
    <h2 class="title font-weight-bold">Load CPU Files</h2>

    <v-file-input
      chips
      multiple
      label="Select Latest Files"
      class="input"
    ></v-file-input>
    <v-file-input
      chips
      multiple
      label="Select Before Files"
      class="input"
    ></v-file-input>
    <div class="separator"></div>
  </div>
</template>

<script>
import "@/assets/css/global.css";

export default {
  setup() {},
};
</script>

<style scoped>
.title {
  padding: 12px 12px;
  margin: 12px 0;
}

.input {
  padding: 0px 12px;
}
</style>
