<template>
    <div>
        <div class="bg-grigio">
            <div class="d-flex justify-content-between ab-container">
                <div>We have a 95% Successful Pass Rate!</div>
                <div>Give us a call to book your tuition! 1-800-555-555</div>
            </div>
        </div>
        <div class="layover">
            <div class="ab-container d-flex justify-content-between align-items-start pt-4 pb-4 ">
            
          
                    <img src="/img/avada-drivers-logo-2x-300x58.png" alt="">
            
        
            <ul class="d-flex ">
                    
                    <li>Home</li>
                    <li><strong>About</strong></li>
                    <li><strong>Prices</strong></li>
                    <li><strong>Courses</strong></li>
                    <li><strong>Locations</strong></li>
                    <li><strong>Blog</strong></li>
                    <li>
                      <span> Book Now</span> </li>
            </ul>
    
           
                
           
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
   font-size: 14px;
}
li:first-child{
    color: #7ABC64;
}
li:first-child::after{
    content: "";
    display: block;
    width: 100%;
    height: 3px;
    background-color:#7ABC64  ;
    margin-top: 10px;
}
// li:last-child{
//     background-color:#7ABC64 ;
//     border-radius: 20px;
// }
span{
    background-color:#7ABC64 ;
     border-radius: 20px;
     padding: 10px 30px;
     transition: 0.3s;
   
}
span:hover{
    filter: contrast(1.50);
}
img{
    width: 250px;
}
.layover{
    background-color: rgba(53, 54, 55, 0.4);
}
strong::after{
    content: "";
    display: none;
    width: 100%;
    height: 3px;
    background-color:#7ABC64  ;
    margin-top: 10px;
   
}

strong:hover::after {
    display: block;
}
strong:hover{
    color: #7ABC64;
}
strong{
    transition-duration: .2s;
    transition-timing-function: linear;
}
</style>