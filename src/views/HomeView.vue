<script setup>
import MainHeader from '../components/Header.vue'
import WorkSpacePart from '../components/WorkSpacePart.vue';
</script>

<template>
<div class="BodyOfHome">
<MainHeader/>
<WorkSpacePart/>
<main>

</main>
</div>
</template>

<style>
.BodyOfHome{
  width:100%;
  height: 100vh;
  background-image: url(../assets/Images/wallpaper.webp) ;
  background-size: cover;
  display:flex;
  flex-direction: column;
}
</style>

