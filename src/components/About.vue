<!-- HTML -->

<template>
 <h3 class="about-me">About Me</h3> 
    <main class="about container-fluid">
      <div class="d-flex flex-column flex-sm-row">
          <div class="container row">
        <div class="col-6 place">
            <div class="spacing d-flex justify-content-center">
          <img class="photo" src="https://i.postimg.cc/wMb6CVwN/FC361385-A476-4456-8788-1-E86-AF8-BB45-E.jpg" alt="me">
        </div>
        </div>
        <div class="col-6 place2">
         <div class="wording">
            <p> I was born in 2002 on the 25 of December, I was born and raised in Cape Town, South Africa.
              I am a Web Development Student currently studying at Life Choices Academy and I matriculated in 2021 at Maitland High School.
              I am a humble young man who was raised by a single mother, living with my uncle and aunt. In my spare time, I love drawing and I'm also a music
              producer. I am a passionate individual who is always up and ready to find new innovative ideas and ways to better
              my craft and as we all know, Technology is the future so our job is to find new, better ways to come out on top!
            </p>
          </div>
        </div>
     </div>
  </div>
    </main>
</template>

<!--JS  -->

<script>
export default {
    
}
</script>

<!-- CSS -->

<style>
    .wording{
    background-color: rgba(236, 232, 232, 0.482);
    text-align:center;
    border-radius:10px ;
    color: azure;
    padding-top: 7rem;
    padding-bottom: 7rem;
    opacity: 0;
    animation: fade 1s;
    animation-delay: 1s;
    animation-fill-mode: forwards;
   }
    .photo{
        border-radius: 10px;
        border-color: black;
        border-style: solid;
        border-width: 2px;
        width: 19rem;
    }
    @keyframes fade {
    from{
        opacity: 0;
    }
    to{
        opacity: 1;
    }
}
@media only screen and (max-width: 720px) {

.container{
  display: flex;
  flex-direction: column; 
  margin: auto;
}
#app{
 padding-top: 2rem;
}
.place{
  margin: auto;
   
 
}
.place2{
  width: 100%;
  margin: auto;
  padding-top: 2rem;
}
.wording{
  width: 19rem;
  padding-top: 2rem;
  padding-bottom: 3rem;
  margin: auto;
}
.about-me{
  padding-top: 4rem;
}
}
</style>