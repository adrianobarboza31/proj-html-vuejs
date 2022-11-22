<template>
    <div class="sfondo  ">
        <div class=" d-flex justify-content-center align-items-center">
            <h2>
            Testimonials
        </h2>
        <p>Here's what our happy drivers had to say about our sevices:</p>
        <img class="pt-5" src="/img/testimonial-sophia.png" alt="">
        <p>
            <em>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perferendis in provident adipisci officia repudiandae quo accusamus maxime, similique ex ullam, sit soluta alias optio consectetur ipsum cumque! Similique, porro error?  
            </em>
          
        </p>
        <strong>Sophia Jones</strong>
        </div>
        
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.sfondo{
    background-image: url('/img/testimonial-background.jpg');
    height: 800px;
    background-size: cover;
    
}
img{
    width: 150px;
}
div.sfondo div{
    flex-direction: column;
    width: 40%;
    margin: auto;
    height: 800px;
    text-align: center;
}
h2{
    font-size: 45px;
}
p{
    font-size: 20px;
    padding-top: 20px;
    color: gray;
}
strong{
    font-size: 20px;
    color: gray;
}

</style>