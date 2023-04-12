<template>
  <h1 class="text-xl font-bold underline"> Weather App Pro</h1>
  <p>{{ apiResponse }}</p>
</template>
<script setup>
    import { reactive,ref, onMounted } from "vue";
    import axios  from "axios";

    const API_KEY = 'bc941981da4e942245bcd2298b5e85d8';
    const apiResponse = ref();

    onMounted(() => {
      axios.get(`https://api.openweathermap.org/data/2.5/weather?lat=44.34&lon=10.99&appid=${API_KEY}`)
          .then(response => {
            apiResponse.value = response;
          })
    })
    
</script>
<style>
  
</style>