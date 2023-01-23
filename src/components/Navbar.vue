<!-- HTML -->

<template>
 <Header>
    <nav class="Nav navbar navbar-dark bg-black fixed-top">
        <div class="container-fluid">
            <img class="logo" src="https://i.postimg.cc/C5PJb9Sv/LK-PORT-1.png" alt="Logos">
          <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
            <div class="offcanvas-header">
              <h5 class="offcanvas-title text-success" id="offcanvasDarkNavbarLabel">Navigation Bar</h5>
              <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
              <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                <li class="menu">
                    <ul class="navbar-nav">
                        <router-link class="link" to="/">Home</router-link> 
                        <router-link class="link" to="/about">About</router-link>
                        <router-link class="link" to="/resume">Resume</router-link> 
                        <router-link class="link" to="/skills">Skills</router-link> 
                        <router-link class="link" to="/projects">Projects</router-link> 
                        <router-link class="link" to="/testimonial">Testimonial</router-link> 
                        <router-link class="link" to="/contact">Contact</router-link>
                        </ul>
                    </li>
                </ul>
            </div>
          </div>
        </div>
      </nav>
    </Header>
</template>

<!--JS  -->

<script>
export default {
    
}
</script>

<!-- CSS -->

<style>
header{
  width: 100%;
}
.link{
    font-family: 'Roboto', sans-serif;
    text-decoration: none;
    padding-bottom: 1rem;
}
    .logo{
        width: 4rem;
        transition: all 2s;
        transform: scale(0.4) rotate();
        animation: awesomeAnimation 7s infinite;
    }
    h5{
        color: rgb(13, 150, 1);
    }
    @keyframes awesomeAnimation{
    0%{
    
       
    }
    30%{
 
    }
    50% {
        transform: rotate(360deg);
    }
    100%{
       
    }
}

</style>