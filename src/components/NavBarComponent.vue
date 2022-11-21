<template>
    <div>
        <div class="bg-grigio">
            <div class="d-flex justify-content-between ab-container">
                <div>We have a 95% Successful Pass Rate!</div>
                <div>Give us a call to book your tuition! 1-800-555-555</div>
            </div>
        </div>
        <div class="layover">
            <div class="ab-container d-flex justify-content-between align-items-center pt-4 pb-4 ">
            <div>
                <div>
                    <img src="/img/avada-drivers-logo-2x-300x58.png" alt="">
                </div>
            </div>
            <div>
                <ul class="d-flex">
                    
                        <li><strong>Home</strong></li>
                        <li><strong>About</strong></li>
                        <li><strong>Prices</strong></li>
                        <li><strong>Courses</strong></li>
                        <li><strong>Locations</strong></li>
                        <li><strong>Blog</strong></li>
                        <li><strong>Book Now</strong></li>
                </ul>
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
.bg-grigio{
    background-color: #353637;
    color: gray;
   font-size: 10px;
   padding: 10px 0;
}
li{
    list-style: none;
    color: white;
    padding: 10px 25px;
   text-transform: uppercase;
   font-weight: 500;
   font-size: 12px;
}
li:last-child{
    background-color:#7ABC64 ;
    border-radius: 20px;
}
img{
    width: 200px;
}
.layover{
    background-color: rgba(53, 54, 55, 0.4);
}
</style>