<template>
    <div class="sfondo ">
        <div class="ab-container relative ">
            <div class="ass">
                <div class="ab-card  pt-4">
                <h2 class="text-center pt-5">Latest News</h2>
                <div class="d-flex justify-content-center pt-5">
                    <div class=" text-center ab-cards ">
                        <img src="/img/blog-choosecar-320x202.jpg" alt="">
                        <div class="pt-2">
                            <strong class="">What car to Start With?</strong>
                        <p class="sottotitolo pt-2">February 7th,2019 | <span>0 Comments</span> </p>
                     
                        <p>Lorem ipsum dolor sit amet consectetur adipisici.
                        </p>
                        </div>
                       
                    </div>
                    <div class=" text-center ab-cards">
                        <img src="/img/blogpost-10and2-320x202.jpg" alt="">
                    <div class="pt-2">
                        <strong>Avada Driving School Expanding</strong>
                        <p class="sottotitolo pt-2">February 7th,2019 | <span>0 Comments</span> </p>
                      
                        <p>Lorem ipsum dolor sit amet consectetur adipisici.
                        </p>
                    </div>
                       
                    </div>
                </div>
                <div class="text-center pt-5 pb-5">
                    <span>More from the blog</span>
                </div>
            </div>
            <div class="">
                <img src="/img/latestnews-bottom.png" alt="">
            </div>
            </div>
          
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.sfondo{
    background-image:url('/img/latestnews-background.jpg') ;
    height: 900px;
    background-size: cover;
    }
    .ab-card{
        background-color: white;
        border-top-left-radius: 10px;
        border-top-right-radius: 10px;
        border-top:7px solid #7f9ea8 ;
    }
    .ab-cards{
        // background-color: aqua;
        // border: 1px solid black;
        width: 50%;
    }
    .ab-cards img{
        width: 85%;
    }
    strong{
        color: #333333;
        font-size: 23px;
        font-weight: 500;
    }
    .sottotitolo{
        color: gray;
       font-size: 12px; 
    }
    p{
        color: gray;
    }
    span{
        background-color: #333333;
        color: white;
        font-weight: 600;
        padding: 10px 30px;
        border-radius: 20px;
        text-transform: uppercase;
        transition: 0.3s;
    }
    span:hover{
        filter: contrast(1.50);
    }
    img{
        max-width: 100%;
    }
    .relative{
        position: relative;
    }
    .ass{
        position: absolute;
        top: -40px;
    }
    .ab-cards span{
        background-color: white;
        color: #333333;
        padding: 0 0;
    }
    h2{
        font-size: 40px;
    }
</style>