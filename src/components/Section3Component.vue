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
            <!-- <div class="ab-card d-flex pt-5">
                <div class="ab-cards text-center">
                    <div class="d-flex justify-content-center pt-5 pb-4">
                        <div class="loader justify-content-center d-flex align-items-center">
                       <div>75%</div>
                    </div>
                    </div>
                    
                    <div class="pb-5">pass rate</div>
                </div>
                <div class="ab-cards text-center">
                    <div class="d-flex justify-content-center pt-5 pb-4">
                        <div class="loader2 justify-content-center d-flex align-items-center">
                       <div>100%</div>
                    </div>
                    </div>
                    
                    <div class="pb-5">referral rate</div>
                </div>
                <div class="ab-cards text-center ">
                    <div class="d-flex justify-content-center align-items-center pt-5 pb-4">
                        <div class="loader3 justify-content-center d-flex align-items-center">
                       <div>25%</div>
                    </div>
                    </div>
                   
                    <div class="pb-5">accident rate</div>
                </div>
            </div>
            <div class="pt-5">
                <h2 class="pt-5 pb-4">Your Instructors</h2>
                <div class="d-flex">
                    <div class="instructorsbox1">
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi deleniti fuga atque saepe voluptates veritatis voluptatibus dolore adipisci molestias ab.
                    </div>
                    <div class="instructorsbox2">
                        <span>more about us</span>
                    </div>
                </div>
            </div>
            <div class="d-flex pt-5 giu giu2">
                <div class="ab-cards text-center ">
                    <div class="d-flex justify-content-center pt-5 pb-4">
                        <img src="/img/instructor-mikehart-400x254.jpg" alt="">
                    </div>
                    
                    <div class="pb-5">
                        <strong>Mike Hart</strong>
                        <p><i class="fa-brands fa-facebook-f"></i> 
                            <i class="fa-brands fa-twitter"></i>
                            <i class="fa-brands fa-instagram"></i>
                        </p>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas, ab.
                        </p>
                    </div>
                </div>
                <div class="ab-cards text-center ">
                    <div class="d-flex justify-content-center pt-5 pb-4">
                        <img src="/img/instructor-johnsmith-400x254.jpg" alt="">
                    </div>
                    
                    <div class="pb-5">
                        <strong>John Smith</strong>
                        <p><i class="fa-brands fa-facebook-f"></i> 
                            <i class="fa-brands fa-twitter"></i>
                            <i class="fa-brands fa-instagram"></i>
                        </p>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas, ab.
                        </p>
                    </div>
                </div>
                <div class="ab-cards text-center ">
                    <div class="d-flex justify-content-center align-items-center pt-5 pb-4">
                        <img src="/img/instructor-angelahart-400x254.jpg" alt="">
                    </div>
                   
                    <div class="pb-5">
                        <strong>Angela Hart</strong>
                        <p><i class="fa-brands fa-facebook-f"></i> 
                            <i class="fa-brands fa-twitter"></i>
                            <i class="fa-brands fa-instagram"></i>
                        </p>
                        <p>
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas, ab.
                        </p>
                    </div>
                </div>
            </div> -->
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
    background-size: contain;
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