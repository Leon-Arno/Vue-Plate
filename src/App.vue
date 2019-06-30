<template>
  <div id="app">
    <b-container>
      <div class="text-center">
        <div>
          <img src="./assets/logo.png" alt="logo" class="vue mt-5" />
        </div>

        <input v-model="message" type="text" />&nbsp;
        <span style="font-size: 12px;">Type in somethiing.</span>
        <h2 class="message">{{ message }}</h2>
      </div>
    </b-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "VueJS rocks!"
    };
  }
};
</script>

<style lang="scss">
#app {
  font-size: 18px;
  font-family: "Avenir Next", sans-serif;
  color: #000000;

  span {
    border: 1px solid #000000;
  }
}
</style>