<!-- HTML -->

<template>

     <div class="container " id="cards">
      <div v-for="pro in projects" key="pro" class="card sort " style="width: 18rem;">
  <img :src="pro.img" class="card-img-top" alt="...">
  <div class="card-bodyspace">
    <h5 class="card-title">{{pro.name}}</h5>
    <p class="card-text">{{pro.more}}</p>
    <div class="card-body">
                <button type="button" class="tie btn btn"><a :href="pro.Git" target="_blank" class="card-link">Github</a></button>
                <button type="button" class="tie btn btn"><a :href="pro.Net" target="_blank" class="card-link">Netify(Live)</a></button>
            </div>
        </div>
  </div>
</div>
   

</template>

<!--JS  -->

<script>
export default {
    name: 'pro',
    data(){
      return{
        projects : [
          {
             id : 1,
             name: "Animation",
             more: "A Square shape which rotates using Animation.",
             img: "https://i.postimg.cc/FFfrRxDT/black-white-spiral-background-1048-16005.webp",
             Git:"https://github.com/Likay01/box.git",
             Net:"https://eloquent-entremet-c8324b.netlify.app/"
            },
            {
             id : 2,
             name: "Vinylique",
             more: "This is a vinyl-selling store I made, called Vinylique.",
             img: "https://i.postimg.cc/ZqLcw8c8/Screenshot-20230119-022653.png",
             Git:"https://github.com/Likay01/E-com-EOM-project.git",
             Net:"https://leafy-froyo-7e1c3b.netlify.app/"
            },
            {
             id : 3,
             name: "Grid",
             more: "This is what I accomplish using grid.",
             img:'https://i.postimg.cc/hGQtzb08/screen.png',
             Git:"https://github.com/Likay01/homework-tryout.git",
             Net:"https://blackpower.netlify.app/"
            },
            {
             id : 4,
             name: "Madused",
             more: "A layout design of a potential statue selling website built using vue.",
             img: "https://i.postimg.cc/jjrRPFRS/Screenshot-20230119-032012.png",
             Git:"https://github.com/Likay01/Madused.git",
             Net:"keen-semolina-ea0912.netlify.app"
            },
            {
             id : 5,
             name: "Poland",
             more: "This is a Home page for a clothing line.",
             img: "https://i.postimg.cc/GpF6543w/POLAND-1-3.png",
             Git:"https://github.com/Likay01/EXERCISE.git",
             Net:"cerulean-gingersnap-26b868.netlify.app"
            },
            {
             id : 6,
             name: "Calculator",
             more: "This is a Calculator I accomplished with JS.",
             img: "https://i.postimg.cc/259pSc96/Screenshot-20230119-033824.png",
             Git:"https://github.com/Likay01/Calculator.git",
             Net:"https://lkcalculator.netlify.app"
            },
        ]
      }
    }
  }  
</script>

<!-- CSS -->

<style>
    #cards{ 
        padding-top: 1px;  
       
    }
    .sort{
        margin: auto; 
     justify-content: space-between;
      background-color: rgba(227, 222, 222, 0.534); 
    }
    @media only screen and (max-width:720px) {
      #cards{
        display: flex;
        flex-direction: column;
        padding-top: 5rem;
        margin: auto;
      }
     
    }
</style>