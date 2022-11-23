<template>
    <div class="relative sfondo">
        <img src="" alt="">
        <div class="ab-container">
           
            <div class="cardcourse text-center ">
                <img cl src="/img/new-corner.jpg" alt="">
                    
                    <h3>Courses</h3>
                <p> placeat officiis perferendis nihil. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad nostrum cupiditate assume praesentium nobis cumque quae culpa. Facilis similique officiis tenetur cum! dsdadadadasd</p>
                <span><strong>Course Information</strong></span>
                
                
            </div>
            <div class="cardcar d-flex justify-content-end pb-5">
                <div class="cardscar text-center">
                    <div class="massimo"> 
                        <img src="/img/courses-passplus-400x399.jpg" alt="">
                    </div>
                   
                    <h5>Pass Plus</h5>
                    <span>
                        <strong>Learn More</strong>
                        </span>
                </div>
                <div class="cardscar text-center">
                    <div class="massimo">
                        <img src="/img/course-intensive-400x399.jpg" alt="">
                    </div>
                   
                    <h5>Intensive Course</h5>
                    <span>
                        <strong>Learn More</strong>
                        </span>
                </div>
                <div class="cardscar text-center">
                    <div class="massimo">
                        <img src="/img/courses-instructor-400x400.jpg" alt="">
                    </div>
                    
                    <h5>Instructors</h5>
                    <span>
                        <strong>Learn More</strong>
                        </span>
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
.massimo{
    width: 100%;
    overflow: hidden;
    height: 226px;
}
.relative{
    position: relative;
}
.cardcourse img{
    position: absolute;
    left: 0;
    top:0;
    width: 17%;
   border-top-left-radius: 10px;
   max-width: 100%;
}
.cardcourse p{
  line-height: 2;
}
.cardcourse span{
    padding: 12px 40px;
    font-size: 14px;
    transition: 0.3s;
}
.cardcourse span:hover{
    filter: contrast(1.50);
}
.cardcourse{
    width: 23%;
    box-shadow: 0px 0px 10px 1px #888888;
    position: absolute;
    top: -20px;
    background-color: white;
    border-radius: 10px;
    padding-top: 40px;
    padding-bottom: 80px;
}
span{
    background-color: #333333;
    color: white;
    padding: 7px 20px;
    text-transform: uppercase;
    font-size: 12px;
    border-radius: 20px;
}
h3{
    font-size: 40px;
}
.cardcourse h3{
    padding-bottom: 20px;
}
.cardcourse p{
    margin-bottom: 40px;
    color: #888888;
    font-size: 15px;
    padding: 0 40px;
}
.cardcar{
    width: 100%;
    
}
.cardscar{
    width: calc((60% - 60px) / 3);
    margin-left: 20px;
    // padding-top: 70px;
    margin-top: 70px;
   overflow: hidden;
   padding-bottom: 20px;
}
.cardscar img:hover{
    transform: scale(1.2);
    opacity: 0.8;
}
.cardscar img{
    width: 100%;
    transition: all .3s ease-in-out;
}
img{
    max-width: 100%;
}
div.cardcar span{
    background-color: white;
    color: #7f9ea8;
    border: 3px solid #7f9ea8;
    transition: 0.3s;
}
div.cardcar span:hover{
    border-color: #333333;
    color: #333333;
}
h5{
    color: #7f9ea8;
    padding-top: 20px;
    padding-bottom: 10px;
}
.sfondo{
    background-image: url('/img/promise-background.jpg');
    background-size: cover;
    background-repeat: no-repeat;

    }
    .ab-cards{
        box-shadow: 0px 0px 10px 1px #888888;
        width: calc((100% - 30px) / 3);
        border-top: 5px solid #7ABC64;
        border-radius: 8px;
       margin: 0 5px;
    }
    .loader{
        width: 200px;
        height: 200px;
        border: 10px solid #F7F7F7;
        border-top-color:#7ABC64;
        border-bottom-color: #7ABC64;
        border-left-color: #7ABC64;
        border-radius: 50%;
    }
    .loader2{
        width: 200px;
        height: 200px;
        border: 10px solid #7ABC64;
       border-radius: 50%;
    }
    .loader3{
        width: 200px;
        height: 200px;
        border: 10px solid #F7F7F7;
        border-top-color: #7ABC64;
        border-radius: 50%;
    }
    .loader,.loader2,.loader3 div{
        font-size: 40px;
        color: gray;
    }
    .instructorsbox1{
        width: 68%;
    }
    .instructorsbox2{
        width: 32%;

    }
    .instructorsbox2 span{
        padding: 10px 110px;
    }
    .ab-cards img{
        max-width: 80%;
    }
    i{
        padding: 0 10px;
    }
    .ab-cards p{
        font-size: 12px;
        color: #888888;
        padding: 0 30px;
    }
 
</style>