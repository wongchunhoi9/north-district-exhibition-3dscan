<template>

<div >
    


      <div >
        <nuxt-link to="tomatowithbutton"><div  class="button-left"><span class="button-arrow-wrap">ᐊ</span></div></nuxt-link>
        <nuxt-link to="pepperwithbutton"><div  class="button-right"><span class="button-arrow-wrap">ᐅ</span></div></nuxt-link>
      </div>

<div class="modelcontainter">
    <iframe title="chickenbreadv3" class="sketchfab-embed-wrapper" src="https://sketchfab.com/models/7af970244a074be8ba4cbf79ef7e4e7d/embed?autospin=1&autostart=1&preload=1">
    </iframe>
</div>

</div>
</template>


<style scoped>

.sketchfab-embed-wrapper {

  position: absolute;
  top: 0;
  left: 3%;
  bottom: 0;
  right: 0;
  width: 94%;
  height:140%;
  justify-content: center;
  align-items: center;
  margin-top: -10%;
  margin-bottom: -10%;
  border: transparent;
}

.modelcontainter {
  background: black;
  background-color: black;

}

.button-left {  
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 3%;
  height:140%;
  text-align: center;
  background-color: black;
  
}

.button-right {  
  position: absolute;
  top: 0;
  left: 97%;
  bottom: 0;
  right: 0;
  width: 3%;
  height:140%;
   text-align: center;
  background-color: black;
}

.button-arrow-wrap {
  top: 50%;
  margin: 0;
  position: absolute;
  color: white;
}

</style>