<template>
  <div>
    <Navbar :logo="logo_src" :alt="app_name" />
    <Home 
    :img1="img1_src" 
    :img2="img2_src" 
    :img3="img3_src"
    :img4="img4_src"
    :img5="img5_src"
    :img6="img6_src"
    :img7="img7_src"
    :img8="img8_src"
    :img9="img9_src"
    :img10="img10_src"
    />
    <Foote />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue"
import Foote from "./components/Foote.vue"
import Home from "./views/Home.vue"

export default {
  data: function() {
    return {
      logo_src: "./img/cine.png",
      app_name: "Lumiere",
      img1_src: "./img/img1.jpg",
      img2_src: "./img/img2.jpg",
      img3_src: "./img/img3.jpg",
      img4_src: "./img/img4.jpg",
      img5_src: "./img/img5.jpg",
      img6_src: "./img/img6.jpg",
      img7_src: "./img/img7.jpg",
      img8_src: "./img/img8.jpg",
      img9_src: "./img/img9.jpg",
      img10_src: "./img/img10.jpg",
      
    }
  },
  components: {
    Navbar,
    Foote,
    Home
  }
}
</script>
<style>
 * {
  font-family: Arial, Helvetica, sans-serif;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  }
  .main-container_home{
    margin: 20px;
    min-height: 500px;
    text-align: left;
  }
 
 .main-container {
    margin: 50px;
    min-height: 250px;

 }

 h2 {
  text-align: center;
  font-size: 42px;
  margin-bottom: 30px;
  color: black;

 }
 .rodape {
    background-color:#03989E;
    height: 100px;
    padding: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: absolute;
    bottom: 0%;
    width: 100%;
 }
 hr{
  margin: 15px;

 }
</style>
