<!-- HTML -->

<template>
    <div class="close">
       <h2 class="skills"><strong>Skills</strong></h2>
        <div>
          <div>
          <img class="end-pic m-a" src="https://i.postimg.cc/fT2P6c26/DSC-3517.jpg" alt="me">
        </div>
       <div class="container mx-auto d-flex align-items-center justify-content-center">
       
        <img class="icons" src="https://i.postimg.cc/VkGHz9v6/html.png" alt="HTML">
         <h6>HTML</h6>
        <img class="icons" src="https://i.postimg.cc/02NYPTwY/css-3.png" alt="CSS">
       <h6>CSS</h6>
        <img class="icons" src="https://i.postimg.cc/FFTSWTB7/bootstrap.png" alt="Bootstrap">
         <h6>Bootstrap</h6>
        <img class="icons" src="https://i.postimg.cc/MKxWBwDB/js.png" alt="Javascript">
        <h6>Javascript</h6>
        <img class="icons" src="https://i.postimg.cc/0jHRFTTk/vue-9-logo-png-transparent.png" alt="Vue">
        <h6>Vue</h6>
       </div>
      </div>
    </div>
</template>

<!--JS  -->

<script>
export default {
    
}
</script>

<!-- CSS -->

<style>
 
.end-pic{
    border-style: solid;
    width: 25rem;
}
h2{
    text-align: center;
    position: relative; 
    
}
.icons{
    width: 5rem;
    justify-content: space-around;
    padding-left: 1rem;
}
h6{
    color: black;
}
.close{
    height: 65vh;
}
@media only screen and (max-width:720px){
.icons{
    width:4rem;
    padding-bottom:2rem;
    margin: auto;
}
.end-pic{
    width:19rem;

}
h6{
   position: relative;
   left: 5rem;
   bottom: 4rem;
}
.container{
  position: relative;
  display: flex;
  flex-direction: column;
  padding-top: 4rem;
  padding-bottom: 3rem;
}
.skills{
    padding-top: 3rem;
}
.close{
    height: 135vh;
}
} 
</style>