<template>
  <div class="main-container_home">
    <hr>
    <h1>Recentes de Bilheteria</h1>
    <img id="img1" :src="img1" :alt="alt">
    <router-link id="img1-url" to="/"/>
    <img id="img_2" :src="img2" :alt="alt">
    <router-link id="img2-url" to="/"/>
    <img id="img_3" :src="img3" :alt="alt">
    <router-link id="img3-url" to="/"/>
    <img id="img_4" :src="img4" :alt="alt">
    <router-link id="img4-url" to="/"/>
    <img id="img_5" :src="img5" :alt="alt">
    <router-link id="img5-url" to="/"/>
    <hr>
    <h1>Comédia</h1>
    <img id="img_6" :src="img6" :alt="alt">
    <router-link id="img6-url" to="/"/>
    <img id="img_7" :src="img7" :alt="alt">
    <router-link id="img7-url" to="/"/>
    <img id="img_8" :src="img8" :alt="alt">
    <router-link id="img8-url" to="/"/>
    <img id="img_9" :src="img9" :alt="alt">
    <router-link id="img9-url" to="/"/>
    <img id="img_10" :src="img10" :alt="alt">
    <router-link id="img10-url" to="/"/>
  
  
  </div>
</template>

<script>
export default {
  name: "Home",
  props: [
  "img1", "alt", 
  "img2", "alt", 
  "img3", "alt", 
  "img4", "alt",
  "img5", "alt",
  "img6", "alt",
  "img7", "alt",
  "img8", "alt",
  "img9", "alt",
  "img10", "alt",
  ],
}
</script>

<style scoped>
 #img1 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 70px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 } 
 #img_2 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 150px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 } 
 #img_3 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 150px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 }
  #img_4 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 150px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 }
  #img_5 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 150px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 }
  #img_6 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 65px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 }
 #img_7 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 150px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 }
 #img_8 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 150px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 }
 #img_9 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 150px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 }
 #img_10 {
  border-radius:16%;
  padding: 15px;
  display: inline-block;
  margin-left: 150px;
  margin-top: 15px;
  height: 300px;
  width: 230px;
 }

</style>
