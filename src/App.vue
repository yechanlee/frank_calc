<template>
  <div class="app">
  <HeaderCal></HeaderCal>
  <BodyCal></BodyCal>
  <FooterCal></FooterCal>
  </div>

</template>

<script>
import HeaderCal from "./components/HeaderCal.vue";
import BodyCal from "./components/BodyCal.vue";
import FooterCal from "./components/FooterCal.vue";



export default {
  name: 'App',
  components: {
  
    BodyCal,
    FooterCal,
    HeaderCal
}
}
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
</style>
