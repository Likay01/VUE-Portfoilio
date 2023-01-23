<!-- HTML -->

<template>
    <div class="overall">
         <div class="container-13 d-flex flex-column flex-lg-row justify-content-center">
             <img class="container-14" src="https://i.postimg.cc/CLHGmdSC/FD2-EB3-AE-716-F-4-E8-D-8-CAB-4-C9319-B36764.jpg" alt="me">
            
            <form
            action="https://formspree.io/f/myyvbyod"
            method="post"
            class="w-100" 
            >
            
            <h1 class="cont"><strong>Contact Me</strong></h1>
              <div class="mb-3 text-center ">
                <label for="exampleInputName" class="form-label text-black">Full Name</label>
                    <input type="text" class="form-control" id="exampleInputName1" name="fullname" aria-describedby="nameHelp" required>
                  </div>
                <div class="mb-3 text-center">
                  <label for="exampleInputEmail1" class="form-label text-black">Email address</label>
                  <input type="email" class="form-control" id="exampleInputEmail1" name="Email" aria-describedby="emailHelp" required>
                  <div id="emailHelp" class="form-text">This is confidential infomation </div>
                </div>
                <div class="mb-3 text-center">
                  <label for="exampleInputmessage1" class="form-label text-black">Message</label>
                  <!-- <textarea name="" id="" cols="30" rows="10"></textarea> -->
                  <input type="text" class="form-control" id="exampleInputmessage1" name="message" required>
                  <div id="messagedHelp" class="form-text"></div>
                </div>
                <div class="icon">
              <a class="icons" href=" https://www.instagram.com/invites/contact/?i=1sbfzuqrobj1p&utm_content=5n0x7a5"><i class="bi bi-instagram"></i></a>
              <a class="icons" href="https://mobile.twitter.com/LindokuhleMgoqi"><i class="bi bi-twitter"></i></a>
            </div>
                <button type="submit" class="btn btn-success">Submit</button>
              </form>
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
  .icon a{
    color: black;
}
.icons{
   display:inline;
}

.cont{
    color: black;
}
input{
  margin: 1rem;
}
.container-14{
  margin: auto;
    width: 25rem;
 border-style: solid;
}  
.overall{
    padding-left: 5rem;
    padding-right: 5rem;
   margin: auto;
   height: 65vh;
}
@media only screen and (max-width:720px) {
  .container-14{
  width: 100%;
  }
  input{
    margin: 0;
  }
  .overall{
    height: 115vh;
  }
}
</style>