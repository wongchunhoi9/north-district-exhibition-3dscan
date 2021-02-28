<template>

<div >
    

    <div >
      <nuxt-link to="honeycombwithbutton"> <b-button class="button-left"  variant="dark"> 	ᐊ </b-button></nuxt-link>
      <nuxt-link to="farmerstickwithbutton"><b-button class="button-right"  variant="dark"> ᐅ </b-button></nuxt-link>
    </div>

<div>
    <iframe title="Tomato" class="sketchfab-embed-wrapper" src="https://sketchfab.com/models/b35456dd949d463f92a1f7902b34d3f7/embed?autospin=1&autostart=1&camera=0&preload=1">
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



.button-left {  
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  width: 3%;
  height:140%;
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