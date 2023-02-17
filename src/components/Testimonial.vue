<!-- HTML -->

<template>
    <div class="container " id="cards">
    <div v-for="test in testimonial" key="test" class="card sorted " style="width: 18rem;" >
        <img :src="test.img" class="card-img-top" alt="...">
  <div class="card-bodyspace">
    <h5 class="card-title">{{test.name}}</h5>
    <p class="card-text">{{test.comment}}</p>
        </div>
            </div>
</div>
</template>

<!--JS  -->

<script>
export default {
    name:"test",
    data() {
        return {
            testimonial: [
                {
                    id: 1,
                    name:"Joel Mukanya",
                    comment:"Lindokuhle is a very creative and well-behaved student. He does enjoy working with his classmates and works well on his project.I will be very delighted to see him get hired as a developer",
                     img: "https://i.postimg.cc/W39QpKyp/Joel-Profile.jpg"
                },
                {
                    id: 2,
                    name:'Sive Shabane',
                    comment:'Always willing to lend a helping hand whenever he can. He creates a good working environment by being supportive. Focused on the task at hand and does it to the point of perfecting it. Respecting of his colleagues.',
                    img:'https://i.postimg.cc/BZk3FGs8/Screenshot-20221103-143935-1-1.jpg'
                },
                {
                    id: 3,
                    name:'Sakhe Mzolisa',
                    comment:'Lindo is a charismatic and bubbly person, innovative would be the word to describe him as he is tree with filled with fresh ideas. A great person to work with, always willing to assist. He standouts amongst a crowd.',
                    img:'https://i.postimg.cc/Kz8bHftL/Sakhe.jpg'
                },
                {
                    id: 4,
                    name:'Candice Amon',
                    comment:' Has a great sense of humor but also has a very mature attitude. Good communication skills and understand his responsibilities are a priority. Has the ability to know when necessary to have a courageous attitude.',
                    img:'https://i.postimg.cc/9MxgMX7y/candice-2022.jpg'
                },
                {
                    id: 5,
                    name:'Timothy Jennike',
                    comment:'Lindokuhle is a guy that can accomplish anything he puts his mind too.  He enjoys learning about new things and helping others when they have trouble with something.',
                    img:'https://i.postimg.cc/x8bW5cYX/1-CDC8663-A9-EC-436-A-AAAD-2-D798659.jpg'
                },
                {
                    id: 6,
                name:'Brandon Swinton',
                    comment:'Lindokuhle Mgoqi is hard worker, Always finds solutions to any problem .He is very committed to the work he represents .I enjoy working with lindokuhle  as a fellow developer.',
                    img:'https://i.postimg.cc/FRXWvDQH/F415-F34-E-3657-4-EAC-91-AF-6682-BFBF.png'
                },
            ]
        }
    }
}
</script>

<!-- CSS -->

<style>
  
    .sorted{
        background-color: rgba(252, 252, 252, 0.518);
        padding-right: 0;
        margin: auto;
    }
    #cards{
     display: flex; 
     flex-wrap: wrap;
     gap: 7rem;
    }
    @media only screen and (max-width:720px) {
      .card{
        margin-top: 1rem;
        margin-bottom: 1rem;
      }
    }
</style>