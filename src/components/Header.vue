<script setup>

</script>

<template>
<header>
 <div class="BodyOfHeader">
  <div class="LeftPart">
   <ul type="none" class="UlInHeader">
    <li>about</li>
    <li>projects</li>
    <li>contacts</li>
    <li>settings</li>
   </ul>
  </div>
  <div class="CenterPart"><b>/soorestful/home</b></div>
  <div class="RightPart" >
   <time>
    2024
    </time>
   </div>
 </div>
</header>
</template>

<style scoped>
header{
 display: flex;
 justify-content: center;
}
.BodyOfHeader{
 background-color: rgb(253, 247, 241);
 height:5vh;
 width:90%;
 margin-top: 1%;
 border: solid black 3px;
 border-radius: 6vh;
 display: flex;
 flex-direction: row;
 align-items: center;
 justify-content: space-between;
 padding: 0% 2% 0% 0%;
}
.UlInHeader{
 display: flex;
 flex-direction: row;
}
.UlInHeader > li{
 padding-right: 5%;
}
.LeftPart{
 width:33%;
}
.CenterPart{
 width:33%;
 display:flex;
 justify-content: center;
}
.RightPart{
 width:33%;
 display:flex;
 justify-content: flex-end;
}
</style>