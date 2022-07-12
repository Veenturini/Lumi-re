<template>
  <div>
    <div id="nav">
      <router-link id="logo-url" to="/">
        <img id="logo" :src="logo" :alt="alt">
      </router-link>
      <router-link to="/">Menu</router-link>
      <router-link to="/Perfil">Perfil</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  props: ["logo", "alt"]
}
</script>

<style scoped>
    #nav {
        background-color:#03989E;
        border-bottom: 4px solid #03989E;
        padding: 15px 50px;
        display: flex;
        justify-content: flex-end;
        align-items: center;
    }
    #nav #logo-url {
        margin: auto;
        margin-left: 0;
    }
    #logo {
        width: 40px;
        height: 40px;
    }
    #nav a{
        color: white;
        text-decoration: none;
        margin: 12px;
        transition: .5s;
    }
     #nav a:hover {
    color: #DAA520;
  }

</style>
