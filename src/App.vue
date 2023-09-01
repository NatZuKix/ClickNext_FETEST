<script setup>
import info from "./components/info.vue";
import infofooter from "./components/footterinfo.vue";
import middle from "./components/middle.vue";
import speaker from "./components/speaker.vue";
import Schedule from "./components/schedule.vue";
import location from "./components/location.vue";
import reward from "./components/reward.vue";
import footerweb from "./components/footerweb.vue";
import footer from "./components/footer.vue";
</script>

<template>
  <div
    class="content w-screen bg-white flex flex-col justify-start items-center"
  >
    <info />
    <infofooter />
    <br />
    <middle />
    <br>
    <speaker/>
    <br>
    <Schedule/>
    <br>
    <location/>
   <br>
  <reward/>
  <footerweb class="mt-2"/>
   <footer/>
    
  </div>
</template>

<style scoped>


</style>

  