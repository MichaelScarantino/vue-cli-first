<template>
  <div id="app">
    <Title/>
    <Hero/>
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Title,
    Hero
  },
};
</script>

<style>
   /* RESET  */
   *{
     margin: 0;
     padding: 0;
     box-sizing: border-box;
   }
   body{
      text-align: center;
   }
</style>
