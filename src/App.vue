<template>
  <div class="container mx-auto my-10">
    <div class="flex justify-around gap-10 mb-14">
      <h1 class="text-2xl font-bold">🌤️ Weather Pro </h1>
      <input type="text" placeholder="Search Location" class=" bg-white bg-opacity-25 w-1/4 border border-white text-white text-sm rounded-full focus:ring-blue-500 focus:border-blue-500 block p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
      <button class="animate-pulse px-6 py-2 rounded-full text-lg bg-violet-200 text-violet-500 flex shadow-lg shadow-violet-400/30 items-center"> <RiFocus3Line class="mr-2" fill="rgb(139 92 246 / 1)" width="25px"/> Current Location</button>
    </div>
    <div class="flex">
      <div class="bg-white p-7 bg-opacity-25 rounded-xl m-3 h-fit">
        <span class=" font-bold text-lg">Now</span>
        <div class="flex my-3 gap-5 items-center">
          <span class=" font-bold text-7xl">19 C</span>
          <img src="./assets/sol.png" width="100" alt="">
        </div>
        <span>Clear Sky</span>
        <hr>
        <span class="flex gap-4 text-sm my-1"><RiCalendar2Line width="25px" fill="white"/> 2010, enro 21</span>
        <span class="flex gap-4 text-sm my-1"><RiMapPinTimeLine width="25px" fill="white"/> Colima Col</span>
      </div>
      <div class="bg-white p-7 bg-opacity-25 rounded-xl m-3">
        <h1 class=" font-semibold text-lg">Today HighLights</h1>
        <div class="flex my-5 gap-4">
          <div class=" bg-black p-5 bg-opacity-25 rounded-xl ">
            <div class="flex items-center justify-between">
              <p class="text-sm">Air Quantity Index</p>
              <div class=" bg-blue-500 px-3 py-1 rounded-full text-sm font-semibold shadow-lg shadow-blue-400/30">Very Poor</div>
            </div>
            <div class="flex my-5 gap-7 items-center text-center">
              <div>
                <RiWindyLine width="60px" fill="white"/>
              </div>
              <div>
                <span class=" text-gray-400 text-sm">PMQS</span>
                <h1 class="font-semibold text-4xl">270</h1>
              </div>
              <div >
                <span class=" text-gray-400 text-sm">SO2</span>
                <h1 class="font-semibold text-4xl">4.53</h1>
              </div>
              <div >
                <span class=" text-gray-400 text-sm">NO2</span>
                <h1 class="font-semibold text-4xl">4.51</h1>
              </div>
              <div >
                <span class=" text-gray-400 text-sm">Q3</span>
                <h1 class="font-semibold text-4xl">23.6</h1>
              </div>
            </div>
          </div>
          <div class=" bg-black p-5 bg-opacity-25 rounded-xl ">
            <div class="flex items-center justify-start">
              <p class="text-sm">Sunrise & Sunset</p>
            </div>
            <div class="flex my-5 gap-7 items-center">
              <div>
                <RiSunLine width="60px" fill="white"/>
              </div>
              <div>
                <span class=" text-gray-400 text-sm">Sunrise</span>
                <h1 class="font-semibold text-4xl">5:30 AM</h1>
              </div>
              <div>
                <RiMoonLine width="60px" fill="white"/>
              </div>
              <div>
                <span class=" text-gray-400 text-sm">Sunset</span>
                <h1 class="font-semibold text-4xl">7:30 PM</h1>
              </div>
            </div>
          </div>
        </div>
        <div class="flex gap-2">
          <div class=" bg-black p-5 bg-opacity-25 rounded-xl w-1/4">
            <span>Humidity</span>
            <div class="mt-5 flex justify-between items-center">
              <RiWaterFlashLine width="50px" fill="white"/>
              <h1 class=" font-semibold text-3xl">43 %</h1>
            </div>
          </div>
          <div class=" bg-black p-5 bg-opacity-25 rounded-xl w-1/4">
            <span>Pressure</span>
            <div class="mt-5 flex justify-between items-center">
              <RiTornadoLine width="50px" fill="white"/>
              <h1 class=" font-semibold text-3xl">1016hPa</h1>
            </div>
          </div>
          <div class=" bg-black p-5 bg-opacity-25 rounded-xl w-1/4">
            <span>Visibility</span>
            <div class="mt-5 flex justify-between items-center">
              <RiEyeLine width="50px" fill="white"/>
              <h1 class=" font-semibold text-3xl">10 km</h1>
            </div>
          </div>
          <div class=" bg-black p-5 bg-opacity-25 rounded-xl w-1/4">
            <span>Feels like</span>
            <div class="mt-5 flex justify-between items-center">
              <RiTempColdLine width="50px" fill="white"/>
              <h1 class=" font-semibold text-3xl">18 C</h1>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="flex gap-5">
      <div>
        <h1 class="text-lg font-semibold">5 Days Forecast</h1>
        <div class="bg-white p-7 bg-opacity-25 rounded-xl w-fill my-5">
          <div class="flex gap-4 items-center">
            <img src="./assets/sol.png" width="45" alt="">
            <span>21 °</span>
            <span class=" text-slate-300">2 March</span>
            <span class=" text-slate-300">Saturday</span>
          </div>
          <div class="flex gap-4 items-center">
            <img src="./assets/sol.png" width="45" alt="">
            <span>21 °</span>
            <span class=" text-slate-300">2 March</span>
            <span class=" text-slate-300">Saturday</span>
          </div>
          <div class="flex gap-4 items-center">
            <img src="./assets/sol.png" width="45" alt="">
            <span>21 °</span>
            <span class=" text-slate-300">2 March</span>
            <span class=" text-slate-300">Saturday</span>
          </div>
          <div class="flex gap-4 items-center">
            <img src="./assets/sol.png" width="45" alt="">
            <span>21 °</span>
            <span class=" text-slate-300">2 March</span>
            <span class=" text-slate-300">Saturday</span>
          </div>
        </div>
      </div>
      <div class="">
        <h1 class=" text-lg font-semibold">Today At</h1>
        <div class="flex gap-5 mt-5 text-center">
          <div class=" bg-white py-3 px-6 gap-5 bg-opacity-25 rounded-xl flex flex-col justify- items-center">
            <span>6 am</span>
            <img src="./assets/sol.png" width="80" alt="">
            <span class=" text-slate-300">19 C</span>
          </div>
          <div class=" bg-white py-3 px-6 gap-5 bg-opacity-25 rounded-xl flex flex-col justify- items-center">
            <span>6 am</span>
            <img src="./assets/sol.png" width="80" alt="">
            <span class=" text-slate-300">19 C</span>
          </div>
          <div class=" bg-white py-3 px-6 gap-5 bg-opacity-25 rounded-xl flex flex-col justify- items-center">
            <span>6 am</span>
            <img src="./assets/sol.png" width="80" alt="">
            <span class=" text-slate-300">19 C</span>
          </div>
          <div class=" bg-white py-3 px-6 gap-5 bg-opacity-25 rounded-xl flex flex-col justify- items-center">
            <span>6 am</span>
            <img src="./assets/sol.png" width="80" alt="">
            <span class=" text-slate-300">19 C</span>
          </div>
          <div class=" bg-white py-3 px-6 gap-5 bg-opacity-25 rounded-xl flex flex-col justify- items-center">
            <span>6 am</span>
            <img src="./assets/sol.png" width="80" alt="">
            <span class=" text-slate-300">19 C</span>
          </div>
          <div class=" bg-white py-3 px-6 gap-5 bg-opacity-25 rounded-xl flex flex-col justify- items-center">
            <span>6 am</span>
            <img src="./assets/sol.png" width="80" alt="">
            <span class=" text-slate-300">19 C</span>
          </div>
          <div class=" bg-white py-3 px-6 gap-5 bg-opacity-25 rounded-xl flex flex-col justify- items-center">
            <span>6 am</span>
            <img src="./assets/sol.png" width="80" alt="">
            <span class=" text-slate-300">19 C</span>
          </div>
          <div class=" bg-white py-3 px-6 gap-5 bg-opacity-25 rounded-xl flex flex-col justify- items-center">
            <span>6 am</span>
            <img src="./assets/sol.png" width="80" alt="">
            <span class=" text-slate-300">19 C</span>
          </div>
        </div>
      </div>
    </div>
    
    
  </div>
</template>
<script setup>
    import { reactive,ref, onMounted } from "vue";
    import axios  from "axios";
    import { RiCalendar2Line, RiMapPinTimeLine, RiWindyLine, RiSunLine, RiMoonLine, RiWaterFlashLine, RiEyeLine, RiFocus3Line, RiTempColdLine, RiTornadoLine} from "vue-remix-icons";

    const API_KEY = 'bc941981da4e942245bcd2298b5e85d8';
    const apiResponse = ref();
    const URL = {
    }


    /* onMounted(() => {
      axios.get(`https://api.openweathermap.org/data/2.5/weather?lat=44.34&lon=10.99&appid=${API_KEY}`)
          .then(response => {
            apiResponse.value = response;
          })
    }) */
    
</script>
<style>
  
</style>