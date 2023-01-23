<template>
  <NavbarVue></NavbarVue>
   <body>
    <router-view></router-view>


    <footer>
    <FooterVue></FooterVue>
  </footer>
   </body>
</template>

<script>
import NavbarVue from './components/Navbar.vue';
import FooterVue from './components/footer.vue';

export default{
  components:{
NavbarVue,
FooterVue
  }
}
</script>

<style>
#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
  padding-top: 7rem;

}
body{
    background-image: url(https://i.postimg.cc/9XgRGqfZ/1105206-illustration-digital-art-minimalism-grass-green-yellow-simple-triangle-pattern-texture-circl.png);
    background-size: cover;
    background-attachment:fixed;
    width: 100vw;
    margin: auto;
    overflow-y: visible;
   
}
nav {
  padding: 30px;
}

nav a {
  
  color: #09c409;
}
nav a.router-link-exact-active {
  color: #bbfeb7;
}
@media only screen and (max-width: 720px) {
  #app{
    padding-top: 3rem;
   
  }
  body{
    overflow-y: visible;

  }
}
</style>
