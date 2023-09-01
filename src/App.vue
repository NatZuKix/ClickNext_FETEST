<script setup>
import info from "./components/info.vue";
import infofooter from "./components/footinfomation.vue";
import middle from "./components/middle.vue";
import speaker from "./components/speaker.vue";
import Schedule from "./components/schedule.vue";
import location from "./components/location.vue";
import reward from "./components/reward.vue";
import footerweb from "./components/footerweb.vue";
</script>

<template>
  <div class="min-[1340px]:visible max-[1339px]:hidden">
  <div class="content w-screen bg-white flex flex-col justify-start items-center  ">
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
  <div class="flex w-4/5 justify-center space-x-10 mt-7">
    <p class="head mt-0.5">ติดต่อสอบถามรายละเอียดเพิ่มเติม </p>
    <img src="./IMG/resorce/phone.png" class="w-fit h-fit -mt-1">
    <p class="head2 text-[#3138A0]">คุณนันทพร ทองเพชร</p>
    <p class="head2 text-[#3138A0] mt-0.5">084-118-4868</p>
  </div>
  </div>
</div>

<div class="min-[768px]:visible max-[767px]:hidden">
  <div class="text-9xl">FOR IPAD</div>
</div>
</template>

<style scoped>
.head{
  font-size: 22px;
  font-family:'Noto Sans Thai', sans-serif;
  font-weight: 500;
}
.head2{
  font-size: 24px;
  font-family:'Noto Sans Thai', sans-serif;
  font-weight: 600;
}

</style>

  