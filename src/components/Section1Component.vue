<template>
    <div class="ab-container d-flex mb-5 giu relative">
        <div class="ab-card pt-5">
            <h2 class="pt-3 pb-3">Get Behind The Wheel</h2>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Modi nesciunt sequi dicta. Repellendus perspiciatis aspernatur, commodi maiores sed animi nostrum.</p>
            <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facere, voluptates dolorem, cum ratione reiciendis accusantium amet placeat, beatae et exercitationem asperiores sed quam omnis voluptatibus reprehenderit sequi aliquid! Saepe, sunt nulla inventore porro esse expedita magnam quod blanditiis enim at optio omnis animi quia consequuntur placeat delectus iure corrupti architecto!
            </p>
        </div>
        <div class=" ">
            <div class="text-center inputcard">
                <h3>First Lesson Free!</h3>
                <p>When you make a block booking with us your first lesson is included free.</p>
                <input type="text" placeholder="Your Name">
                <br>
                <input type="text" placeholder="Email">
                <br>
                <input type="text" placeholder="Telephone">
                <br>
                <input class="mb-4" type="text" placeholder="Location">
                <br>
                <span  class=""><strong>Request a Callback</strong> </span>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
p{
    font-size: 22px;
    color: grey;
}
p:last-child{
    font-size: 16px;
}
.ab-card{
    width: 50%;
    padding-right: 30px;
}
h3{
    color: #333333;
    padding: 25px 0;
}
.inputcard{
    box-shadow: 0px 0px 10px 1px #888888;
    position: absolute;
    border-radius: 10px;
    top: -30px;
    right: 0;
    background-color: white;
    width: 45%;
    padding-bottom: 50px;
    padding-top: 20px;
}
.relative{
    position: relative;
}
div.inputcard p{
    font-size: 15px;
    padding: 0 29px;
}
input{
    width: 85%;
    background-color: #F7F7F7;
    border: 1px solid #e5e8eb;
    margin-top: 30px;
    font-size: 13px;
    padding: 15px 8px;
}
span{
    background-color: #333333;
    color: white;
    padding: 10px 30px;
    border-radius: 15px;
    text-transform: uppercase;
    font-size: 13px;
    transition: 0.3s;
}
span:hover{
    filter: contrast(1.50);
}
.giu{
    padding-bottom: 100px;
}
p{
    line-height: 2;
}
h2{
    font-size: 40px;
}
</style>