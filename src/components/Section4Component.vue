<template>
    <div class="ab-container relative">
        <div class="ab-card d-flex pt-5">
                <div class="ab-cards text-center">
                    <div class="d-flex justify-content-center pt-5 pb-4">
                        <div class="loader justify-content-center d-flex align-items-center">
                       <div>75%</div>
                    </div>
                    </div>
                    
                    <div class=" pt-3 ab-down">pass rate</div>
                </div>
                <div class="ab-cards text-center">
                    <div class="d-flex justify-content-center pt-5 pb-4">
                        <div class="loader2 justify-content-center d-flex align-items-center">
                       <div>100%</div>
                    </div>
                    </div>
                    
                    <div class=" pt-3 ab-down">referral rate</div>
                </div>
                <div class="ab-cards text-center ">
                    <div class="d-flex justify-content-center align-items-center pt-5 pb-4">
                        <div class="loader3 justify-content-center d-flex align-items-center">
                       <div>25%</div>
                    </div>
                    </div>
                   
                    <div class=" pt-3 ab-down">accident rate</div>
                </div>
            </div>
            <div class="pt-5 bo">
                <h2 class="pt-5 pb-4">Your Instructors</h2>
                <div class="d-flex  ">
                    <div class="instructorsbox1">
                   <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sequi deleniti fuga atque saepe voluptates veritatis voluptatibus dolore adipisci molestias ab.</p>     
                    </div>
                    <div class="instructorsbox2">
                        <span>more about us</span>
                    </div>
                </div>
            </div>
            <div class="d-flex pt-5 ass">
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
       background-color: white;
       color: #7f9ea8;
       font-size: 18px;
       text-transform: uppercase;
       font-weight: 600;
    }
    .loader{
        width: 220px;
        height: 220px;
        border: 10px solid #F7F7F7;
        border-top-color:#7ABC64;
        border-bottom-color: #7ABC64;
        border-left-color: #7ABC64;
        border-radius: 50%;
    }
    .loader2{
        width: 220px;
        height: 220px;
        border: 10px solid #7ABC64;
       border-radius: 50%;
    }
    .loader3{
        width: 220px;
        height: 220px;
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
        transition: 0.3s;
    }
    .instructorsbox2 span:hover{
    filter: contrast(1.50);
}
    .instructorsbox2 span{
        padding: 13px 130px;
       font-size: 15px;
       font-weight: 600;
    }
    .ab-cards img{
        max-width: 80%;
    }
    i{
        padding: 0 10px;
        padding-top: 15px;
        font-size: 15px;
    }
    .ab-cards p{
        font-size: 13px;
        color: #888888;
        padding: 0 50px;
    }
    .ass{
        position: absolute;
        top:740px
    }
    .bo{
        padding-bottom: 450px;
    }
    .loader,.loader2,.loader3 {
        color: #7f9ea8;
        font-size: 50px;
    }
    .loader3 div{
        color: #7f9ea8;
        font-size: 50px;
    }
    .ab-down{
        padding-bottom: 70px;
    }
    h2{
        font-size: 40px;
    }
    .instructorsbox1 p{
        line-height: 2;
        font-size: 20px;
    }
    strong{
        font-weight: 700;
    }
</style>