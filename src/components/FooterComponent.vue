<template>
  <div class="sfondo d-flex align-items-center">
    <div class="ab-container d-flex row">
      <div class="ab-card col-3">
        <img src="/img/avada-drivers-logo-2x-300x58.png" alt="">
        <p>Avada Driving school is the right choice for experienced drivers looking for a refresher course, or the brand new driver wanting to pass first time. </p>
      </div>
      <div class="col-3">
        <h5>contact details</h5>
        <div class="d-flex" v-for="(value) in contatti" >
          <i :class="value.loghi"></i>
         <p>{{value.details}}</p> 
        </div>
      </div>
      <div class="col-3">
        <h5>courses</h5>
        <div class="d-flex cv" v-for="(value) in corsi" >
          <i class="fas fa-arrow-circle-right"></i>
         <p>{{value}}</p> 
        </div>
      </div>
      <div class="col-3">
        <img src="/img/footer-ad-grid.png" alt="">
      </div>
    </div>
  </div>
  <div class="sfondo2 ">
    <div class="ab-container d-flex justify-content-between align-items-center hh">
      <div>© Copyright 2012 - 2022 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</div>
    <div>
      <i class="fab fa-facebook-f"></i>
      <i class="fa-brands fa-twitter"></i>
      <i class="fa-brands fa-youtube"></i>
      <i class="fa-brands fa-instagram"></i>
    </div>
    </div>
  </div>
  <!-- <div class="sfondo2">
   <div class="ab-container">
    <p>© Copyright 2012 - 2022 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>
    <p>
      <i class="fab fa-facebook-f"></i>
      <i class="fa-brands fa-twitter"></i>
      <i class="fa-brands fa-youtube"></i>
      <i class="fa-brands fa-instagram"></i>
    </p>
   </div>
  </div> -->
</template>

<script>
  export default {
    data(){
      return{
        contatti:[
          {
            loghi:'fa-solid fa-house',
            details:'12345 North Main Street, New York, NY 555555 '
          },
          {
            loghi:'fa-solid fa-phone',
            details:'1.800.555.6789 '
          },{
            loghi:'fa-solid fa-envelope',
            details:'info@your-domain.com'
          },
          {
            loghi:'fa-solid fa-crutch',
            details:' Theme_fusion.com'
          }
        ],
        corsi:[
          'Pass Plus','Intensive Corse', 'Automatic','Instructor Training'
        ]
        }
      }
    }
    
</script>

<style lang="scss" scoped>
  .sfondo{
        background-image: url('/img/footer-background-color.jpg');
        height: 400px;
        background-size: cover;
    }
    img{
      max-width: 100%;
    }
    // .col-3{
    //   border: 1px solid red;
    // }
    p{
      color:#929aa3;
      font-size: 13px;
      margin-block-start: 1em;
    margin-block-end: 1em;
    padding-left: 10px;
    padding-right: 10px;
    }
    div{
      color: #929aa3;
    }
    h5{
      color: white;
      text-transform: uppercase;
      font-size: 18px;
    }
    i{
      padding-top: 15px;
    }
    .cv{
      color: #7ABC64;
    }
    .cv p{
      color: #7ABC64;
    }
    .ab-card img{
      width: 80%;
    }
    .sfondo2{
      height:150px ;
     background-color: #333333;
    }
    .hh{
      height: 150px;
      font-size: 12px;
    }
    .hh i{
      padding: 0 7px;
      font-size: 16px;
    }
</style>