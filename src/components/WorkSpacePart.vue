<script setup>
import Projects from './lilapps/projects/Projects.vue';
import About from './lilapps/about/About.vue';
</script>

<template>
<div class="WorkSpacePart">
<div class="AppIcon" onclick="document.getElementById('ProjectProcess').style.display= 'flex' ">
<img src="./lilapps/projects/icon.svg" alt="err" >
<b>Projects</b>
</div>
<div class="AppIcon" onclick="document.getElementById('AboutProcess').style.display= 'flex' ">
<img src="./lilapps/about/icon.svg" alt="err" >
<b>About</b>
</div>
<Projects class="Appprojects"/>
<About class="Appabout"/>
</div>
</template>

<style scoped>
.WorkSpacePart{
 height: 100vh;
 padding: 2% 0% 2% 2%;
 display:flex;
 flex-direction: column;
 overflow: hidden;
}
.AppIcon{
 display: flex;
 width:60px;
 flex-direction: column;
 text-align: center;
 margin:1%;
}
.Appprojects{
 position: absolute;
 top:5%;
 left:50%;
 z-index:0;
}
.Appabout{
 position: absolute;
 top:5%;
 left:50%;
 z-index:1;
}
</style>