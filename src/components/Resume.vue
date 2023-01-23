<!-- HTML -->

<template>
    <main class="focus container-fluid">
<div class="separate d-flex flex-column flex-sm-row">
  <div class="collect">
  <img class="edu-pic" src="https://i.postimg.cc/fT2P6c26/DSC-3517.jpg" alt="me">
</div>
  <div class="container-9 text-lg-center">
    <div class="text-in"> 
    <strong>
      <h1 class="text-white text-center">Work/Education</h1>
    </strong>
    <table v-for="info in resume" :key="info" class="table text-white">
      <tbody>
        <tr>
          <th scope="row">{{info.Name}}
            <p class="description">{{ info.desc }}</p>
        </th>
            <td></td>
            <td></td>
            <td><strong>{{info.year}}</strong></td>
          </tr>
            </tbody>
          </table>
        </div>
        </div>
      
</div>

    </main>
</template>

<!--JS  -->

<script>
export default {
    name:"info",
    data() {
        return {
            resume: [
                {
                    id: 1,
                    Name:'Maitland High School',
                    year:'2017 - 2021'
                },
                {
                    id: 2,
                    Name:'Maitland High School',
                    desc:'matriculated with a Bachelor Pass',
                    year:'2021'
                },
                {
                    id: 3,
                    Name:'Maitland High School',
                    desc:'RCL Member (Treasurer role)',
                    year:'2021'
                },
                {
                    id: 4,
                    Name:'Life Choices Academy',
                    desc:'aspiring to become a Web Development',
                    year:'2022'
                }
            ]
        }
    }
}
</script>

<!-- CSS -->

<style>
    .edu-pic{
   width: 25rem;
   border-radius: 10px;
   padding-top: 5rem;
}
.container-9{
    background-color: rgba(0, 0, 0, 0.63);
    border-radius: 10px;
    width: 100%;
}
.separate{
    flex-direction: column;
   
   padding-bottom: 50px;
}
.collect{
    padding-right:10px ;
}
.text-in{
    width: 100%;
}
.description{
    color: rgb(18, 243, 7);
}
@media only screen and (max-width:720px) {
.edu-pic{
    width: 100%;
}
}
</style>