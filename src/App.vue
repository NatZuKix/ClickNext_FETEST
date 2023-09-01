<script setup>
import info from "./components/info.vue";
import infofooter from "./components/footinfomation.vue";
import middle from "./components/middle.vue";
import speaker from "./components/speaker.vue";
import Schedule from "./components/schedule.vue";
import location from "./components/location.vue";
import reward from "./components/reward.vue";
import footerweb from "./components/footerweb.vue";

import info_MOBILE from "./components/MOBILE/info.vue";
import infofooter_MOBILE from "./components/MOBILE/footinfomation.vue";
import middle_MOBILE from "./components/MOBILE/middle.vue";
import speaker_MOBILE from "./components/MOBILE/speaker.vue";
import Schedule_MOBILE from "./components/MOBILE/schedule.vue";
import location_MOBILE from "./components/MOBILE/location.vue";
import reward_MOBILE from "./components/MOBILE/reward.vue";
import footerweb_MOBILE from "./components/MOBILE/footerweb.vue";

import info_IPAD from "./components/IPAD/info.vue";
import infofooter_IPAD from "./components/IPAD/footinfomation.vue";
import middle_IPAD  from "./components/IPAD/middle.vue";
import speaker_IPAD  from "./components/IPAD/speaker.vue";
import Schedule_IPAD  from "./components/IPAD/schedule.vue";
import location_IPAD  from "./components/IPAD/location.vue";
import reward_IPAD  from "./components/IPAD/reward.vue";
import footerweb_IPAD  from "./components/IPAD/footerweb.vue";
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

<div class="min-[1338px]:hidden max-[945px]:hidden">
   <div class="content w-screen bg-white flex flex-col justify-start items-center  ">
    <info_IPAD />
    <infofooter_IPAD />
    <br />
    <middle_IPAD />
    <br>
    <speaker_IPAD/>
    <br>
    <Schedule_IPAD/>
    <br>
    <location_IPAD/>
   <br>
  <reward_IPAD/>
  <footerweb_IPAD class="mt-2"/>
  <div class="flex w-4/5 justify-center space-x-10 mt-7">
    <p class="headipad mt-0.5">ติดต่อสอบถามรายละเอียดเพิ่มเติม </p>
    <img src="./IMG/resorce/phone.png" class="w-fit h-fit -mt-1">
    <p class="head2ipad text-[#3138A0]">คุณนันทพร ทองเพชร</p>
    <p class="head2ipad text-[#3138A0] mt-0.5">084-118-4868</p>
  </div>
  </div>
</div>

<div class="min-[945px]:hidden">
  <div class="content w-screen bg-white flex flex-col justify-start items-center  ">
    <p>ddd</p>
    <info_MOBILE />
    <infofooter_MOBILE />
    <br />
    <middle_MOBILE />
    <br>
    <speaker_MOBILE/>
    <br>
    <Schedule_MOBILE/>
    <br>
    <location_MOBILE/>
   <br>
  <reward_MOBILE/>
  <footerweb_MOBILE class="mt-2"/>
  <div class="flex w-4/5 justify-center space-x-10 mt-7">
    <p class="headipad mt-0.5">ติดต่อสอบถามรายละเอียดเพิ่มเติม </p>
    <img src="./IMG/resorce/phone.png" class="w-fit h-fit -mt-1">
    <p class="head2ipad text-[#3138A0]">คุณนันทพร ทองเพชร</p>
    <p class="head2ipad text-[#3138A0] mt-0.5">084-118-4868</p>
  </div>
  </div>
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

.headipad{
  font-size: 18px;
  font-family:'Noto Sans Thai', sans-serif;
  font-weight: 500;
}
.head2ipad{
  font-size: 20px;
  font-family:'Noto Sans Thai', sans-serif;
  font-weight: 600;
}

</style>

  