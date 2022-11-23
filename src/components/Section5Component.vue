<template>
    <div class="sfondo  ">
        <div class=" d-flex justify-content-center align-items-center altezza">
            <h2>
            Testimonials
        </h2>
        <p>Here's what our happy drivers had to say about our sevices:</p>
        <img class="pt-5" :src="testimonials[index].imag" alt="">
        <p>
            <em>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perferendis in provident adipisci officia repudiandae quo accusamus maxime, similique ex ullam, sit soluta alias optio consectetur ipsum cumque! Similique, porro error?  
            </em>
          
        </p>
        <strong>{{testimonials[index].name}}</strong>
            <br>
            <p ><span class="fa-circle"  v-for="(value,indexx) in testimonials" :key = "indexx" :class="indexx===[index] ? 'fa-solid':'fa-regular' " @click="corrente(value,indexx)"></span>
            </p>
        </div>
        
    </div>
</template>

<script>
    export default {
        data(){
            return{
                index:0,
                testimonials:[
                    {
                        imag:'/img/testimonial-sophia.png',
                        name:'Sophia Jones',
                    },
                    {
                        imag:'/img/testimonial-harold.png',
                        name:'Harold Green',
                    },
                    {
                        imag:'/img/testimonial-grant.png',
                        name:'Grant Harvey',
                    },
                    {
                        imag:'/img/testimonial-kate.png',
                        name:'Kate Lewis',
                    },
                    {
                        imag:'/img/testimonial-kelly.png',
                        name:'Kelly Johnson',
                    },
                ]
            }
        },
        methods:{
            corrente(value,indexx){
                this.index=indexx
                console.log(this.index)
            },
            avanti(){
                this.index=this.index+1
                if( this.index>4){
                    this.index=0
                }
            },
            slider(){
                this.autoslider= setInterval(()=>{
                    this.avanti()
                   
                },2000)
            }
        },
        mounted(){
            this.slider();  
           
        }
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
span{
   margin: 0 5px;
}
</style>