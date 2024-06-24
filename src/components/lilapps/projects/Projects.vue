<script setup>
import Borders from '@/components/Borders.vue';
</script>

<template>

  <div class="InProjects">
   <div class="TopProjects">
    <div class="leftpart"></div>
    <div class="rightpart"><button class="redbut"></button></div>
   </div>
   <div class="InAppExp">
    <h1>TEST</h1>
   </div>
  </div>
</template>

<style scoped>
.InProjects{
 background-color: white;
 width: 40vh;
 height: 25vh;
 display: flex;
 flex-direction: column;
 border-radius: 2vh;
}
.TopProjects{
 display: flex;
 background-color: rgb(231, 231, 231);
 border-radius: 2vh 2vh 0vh 0vh;
}
.TopProjects > .leftpart {
 width:70%;
}
.TopProjects > .rightpart{
 width: 30%;
 display: flex;
 justify-content: flex-end;
 padding:3%;
}
.redbut{
 background-color: red;
 border: none;
 height: 15px;
 width: 15px;
 border-radius: 50vh;
}
.InAppExp{
 display: flex;
 height: 100%;
 align-items: center;
 justify-content: center;
 color:pink;
}
</style>