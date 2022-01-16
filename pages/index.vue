<template>
  <div id="body">
    <div id="body-content">
      <div id="main">
        <b>Long Now Boston</b> fosters<br>
        long-term thinking to influence<br>
        the trajectory of today's decision<br>
        making to ensure sustained<br>
        human thriving
        <br>
        <v-btn>Learn More></v-btn>
      </div>
    </div>
    <div id="bottom">
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
 #body {
   width: 100%;
   height: 88vh;
   overflow: hidden !important;
   display: grid;
   grid-template-rows: 1fr 150px;
 }
 #body-content {
   /* background-image: url("https://picsum.photos/1200/800"); */
   background-image: url("~assets/lnb-frontpage-01_v04_01.png");
   background-size: cover;
   /*    background-attachment: fixed; */
   background-position: center center;
   width: 100%;
   height: 100%;

   display: grid;
   grid-template-columns: 10% 1fr;
   grid-template-rows: 20% 1fr 150px;
   grid-column-gap: 0px;
   grid-row-gap: 0px;
 }

 #main {
   grid-area: 2 / 2 / 3 / 3;
   font-size: 3.5em;
   line-height: 1.2em;
   text-shadow: 1px 1px 2px black;
 }

 #bottom {
   width: 100%;
   height: 10vh;
   background-image: url("~assets/bottom-bar-with-text.png");
   background-size: cover;
   background-position: center center;
   width: 100%;
   height: 100%;
 }


</style>
