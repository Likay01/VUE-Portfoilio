<!-- HTML -->

<template>
    <main class="container-fluid">
   <div class="out-lay d-flex">
    
    
<div class="container row all">
        <div class="first col-6">
       <div class="land flex-container container-2 align-content-end">
       <h1>Hi there!</h1>
       <h1>I'm Lindokuhle Mgoqi </h1>
       <div class="text-content">
         <h4 class="web">I am a Web development Student.</h4>
         <button type="button" class="btn btn"><a class="click" href="/about">About Me</a></button>
         </div>
     </div>
        </div>
        <div class="col-6 img-block">
           <div class="d-flex justify-content-center">
           <img class="container-1" src="https://i.postimg.cc/VvBcnH0C/FD2-EB3-AE-716-F-4-E8-D-8-CAB-4-C9319-B36764.jpg" alt="" srcset="">
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
.land{
margin-top: 5rem;
color: black;
}
 .container-1{
    width: 25rem;
    border-radius: 50%;
    border-style: groove;
    border-width: 10px;
    border-color: rgb(5, 99, 6);
    opacity: 0;
    animation: fade 1s;
    animation-delay: 1s;
    animation-fill-mode: forwards;
 }
 
 .container{
    margin: auto;
    padding-top: 2rem;
 }
 main{
   margin: auto;
   height:65vh;
   
 }
 .click{
    text-decoration: none;
    font-size: large;
 }
 .first{
   position: relative;
   animation: fadeinLeft 2s  ;
   animation-direction: alternate;
 }
 @keyframes fade {
    from{
        opacity: 0;
    }
    to{
        opacity: 1;
    }
}
@keyframes fadeinLeft {
   from{
      opacity: 0;
   }
   to{
      opacity: 1;
   }
}
@media only screen and (max-width: 720px) {
.first{
margin: auto;
}
.container-1{
   width: 13rem;

}
.img-block{
   padding-top: 5rem;
   display: none;
 }
.all{
    position: relative;
    display: flex;
    flex-direction: column;
   width: 100vw; 
   align-items: center;
   
}
main{
   height: 75vh;
}
.first{
   margin: 0;
  text-align: center;
}

}

</style>