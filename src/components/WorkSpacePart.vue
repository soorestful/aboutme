<script setup>
import Projects from './lilapps/projects/Projects.vue';
</script>

<template>
<div class="WorkSpacePart">
<div class="MiniApp">
<img src="./lilapps/Projects/icon.svg" alt="" >
<b>Projects</b>
</div>
<Projects class="AppProject"/>
</div>
</template>

<style scoped>
.WorkSpacePart{
 padding: 2% 0% 2% 5%;
 display:grid;
 position: relative;
}
.MiniApp{
 display: flex;
 width:60px;
 flex-direction: column;
 text-align: center;
}
.AppProject{
 position: absolute;
 top:60%;
 left:60%
}
</style>