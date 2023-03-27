<!-- HTML -->

<template>
    <div class="close">
       <h2 class="skills"><strong>Skills</strong></h2>
        <div>
          <div>
          <img class="end-pic m-a" src="https://i.postimg.cc/fT2P6c26/DSC-3517.jpg" alt="me">
        </div>
       <div class="container mx-auto d-flex align-items-center justify-content-center">
       
    <div class="zoom-in">
        <img class="icons btn " data-bs-toggle="modal" data-bs-target="#exampleModal" src="https://i.postimg.cc/VkGHz9v6/html.png" alt="HTML">
         <h6>HTML</h6>

<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5 text-black" id="exampleModalLabel">HTML</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body ">
       <P class="text-black">HTML stands for Hyper Text Markup Language, which is the most widely used language on Web to develop web pages. </P>
       <H6 class="text-black">HTML Knowledge</H6>
</div>
      <div class="modal-body">
       <div class="progress">
  <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 90%"><h6 class="perc">90%</h6></div>
</div> 

    </div>
    </div>
  </div>
</div>
        </div>

       <div class="zoom-in">
         <img class="icons btn " data-bs-toggle="modal" data-bs-target="#exampleModal" src="https://i.postimg.cc/02NYPTwY/css-3.png" alt="CSS">
       <h6>CSS</h6>

       <!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5 text-black" id="exampleModalLabel">CSS</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body ">
       <P class="text-black">CSS is the language we use to style an HTML document. CSS describes how HTML elements should be displayed. </P>
       <H6 class="text-black">CSS Knowledge</H6>
</div>
      <div class="modal-body">
       <div class="progress">
  <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 95%"><h6 class="perc">95%</h6></div>
</div> 

    </div>
    </div>
  </div>
</div>
    </div>

   <div class="zoom-in">
    <img class="icons" src="https://i.postimg.cc/FFTSWTB7/bootstrap.png" alt="Bootstrap">
         <h6>Bootstrap</h6>
   </div>
   <div class="zoom-in">
    <img class="icons" src="https://i.postimg.cc/MKxWBwDB/js.png" alt="Javascript">
        <h6>Javascript</h6>
   </div>
   <div class="zoom-in">
    <img class="icons" src="https://i.postimg.cc/0jHRFTTk/vue-9-logo-png-transparent.png" alt="Vue">
        <h6>Vue</h6>
   </div> 
       </div>
      </div>
    </div>
</template>

<!--JS  -->

<script>

</script>

<!-- CSS -->

<style>
.perc{
    margin: auto;
}
.modal-content{
    background-color: rgba(255, 255, 255, 0.349);
    background-size:cover ;
 
}

 .icons:hover {
  -ms-transform: scale(1.5); /* IE 9 */
  -webkit-transform: scale(1.5); /* Safari 3-8 */
  transform: scale(1.5); 
}

.end-pic{
    border-style: solid;
    width: 25rem;
}
h2{
    text-align: center;
    position: relative; 
    
}
.icons{ 
    transition: transform .3s;
    width: 5rem;
    justify-content: space-around;
 padding-left: 1rem;
}
h6{
    color: black;
    padding-left: 1rem;
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