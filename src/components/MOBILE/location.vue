<script setup>

</script>

<template>
   <div class="w-full rounded-2xl bg-gradient-to-b from-[#5D97E3] to-[#0C2192] p-18">
      <div class="flex  items-center text-white py-8 "> 

        <img src="../../IMG/resorce/locaicon.png" class="w-12 h-auto mr-5 -mt-16 ml-20">
        <div class="flex flex-col">
          <p class="locationL1">ณ ห้องแกรนด์บอลรูม ชั้น 4</p>
          <p class="locationL2">โรงแรมพูลแมน กรุงเทพแกรนด์ สุขุมวิท</p>
          <button class="w-5/6 h-12 bg-[#359EFF] rounded-full mt-3 text-sm font-noto text-white hover:bg-slate-600" >ดูแผนที่ google map</button>
        </div>
        <img src="../../IMG/resorce/room.png" class="w-32 h-auto  ml-10   "/>
      </div>

    </div>
</template>

<style scoped>
.locationL2{
font-family: 'Noto Sans Thai', sans-serif;
font-size: 14px;
font-weight: 500;
}
.locationL1{
font-family: 'Noto Sans Thai', sans-serif;
font-size: 18px;
font-weight: 700;
}
</style>
