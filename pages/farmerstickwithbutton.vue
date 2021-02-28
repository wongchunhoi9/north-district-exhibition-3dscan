<template>

<div >
    

    <div >
      <nuxt-link to="raddishwithbutton"> <b-button class="button-left"  variant="dark"> ᐊ </b-button></nuxt-link>
      <nuxt-link to="honeycombwithbutton"><b-button class="button-right"  variant="dark"> ᐅ </b-button></nuxt-link>
    </div>

<div class="modelcontainter">
    <iframe title="farmerstickzip" class="sketchfab-embed-wrapper" src="https://sketchfab.com/models/474aaceb6ae249919f48112acf4fb2ce/embed?autospin=1&autostart=1&preload=1&transparent=0">
    
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
  /* background-image:  url('~assets/UI/buttonleft.svg'); */
}
.button-right {  
  position: absolute;
  top: 0;
  left: 97%;
  bottom: 0;
  right: 0;
  width: 3%;
  height:140%;
  /* background-image:  url('~assets/buttonleft'); */
}

</style>