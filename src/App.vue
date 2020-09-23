<template>
  <div id="app">
    <meta charset="utf-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, shrink-to-fit=no"
    />
    <img
      src="https://cdn.discordapp.com/attachments/748191031870226462/758350643710132224/dbt4epd-5198725c-78be-4fc5-8100-ce8ede877ac3.gif"
      class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto"
    />
    <anime />
  </div>
</template>

<script>
import anime from "./components/anime";
export default {
  name: "App",
  components: {
    anime,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  background-image: url("https://cdn.discordapp.com/attachments/748191031870226462/758349632807239691/934905.jpg");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  height: 100vh;
}
</style>
