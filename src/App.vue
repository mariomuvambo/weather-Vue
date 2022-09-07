<template>
<weather />

</template>
<script >
import Weather from './components/Weather.vue';
export default{
  name: 'app',
  components: {
    Weather,
  }
};

</script>

<style>

 body {
  overflow-y: hidden;
  height: 100vh;
  background-image: url('./assts/wheather.jpg');
  background: linear-gradient(
    -185deg,
    rgb(16, 46, 102) 5%,
    rgba(200, 208, 208, 0.51) 75%
  );
} 

@media only screen and (min-width: 360px) and (max-width: 908px) {
  body {
    overflow-y: auto;
  }
}


</style>





 



