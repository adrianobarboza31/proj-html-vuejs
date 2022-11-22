<template>
    <div class="relative sfondo">
        <img src="" alt="">
        <div class="ab-container">
            <div class="cardcourse text-center pb-5">
                <h3>Courses</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad nostrum cupiditate assume praesentium nobis cumque quae culpa. Facilis similique officiis tenetur cum! dsdadadadasd</p>
                <span><strong>Course Information</strong></span>
            </div>
            <div class="cardcar d-flex justify-content-end pb-5">
                <div class="cardscar text-center">
                    <img src="/img/courses-passplus-400x399.jpg" alt="">
                    <h5>Pass Plus</h5>
                    <span>
                        <strong>Learn More</strong>
                        </span>
                </div>
                <div class="cardscar text-center">
                    <img src="/img/course-intensive-400x399.jpg" alt="">
                    <h5>Intensive Course</h5>
                    <span>
                        <strong>Learn More</strong>
                        </span>
                </div>
                <div class="cardscar text-center">
                    <img src="/img/courses-instructor-400x400.jpg" alt="">
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
.relative{
    position: relative;
}
.cardcourse{
    width: 25%;
    box-shadow: 0px 0px 10px 1px #888888;
    position: absolute;
    top: -20px;
    background-color: white;
    border-radius: 10px;
    padding-top: 40px;
}
span{
    background-color: #7ABC64;
    color: white;
    padding: 7px 17px;
    text-transform: uppercase;
    font-size: 12px;
    border-radius: 15px;
}
.cardcourse h3{
    padding-bottom: 20px;
}
.cardcourse p{
    margin-bottom: 40px;
    color: #888888;
    font-size: 12px;
    padding: 0 40px;
}
.cardcar{
    width: 100%;
    
}
.cardscar{
    width: calc((65% - 60px) / 3);
    padding-left: 20px;
    padding-top: 70px;
   
}
img{
    max-width: 100%;
}
div.cardcar span{
    background-color: white;
    color: #7f9ea8;
    border: 3px solid #7f9ea8;
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