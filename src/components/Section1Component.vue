<template>
    <div class="ab-container d-flex mb-5 giu">
        <div class="ab-card pt-5">
            <h2 class="pt-3 pb-3">Get Behind The Wheel</h2>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Modi nesciunt sequi dicta. Repellendus perspiciatis aspernatur, commodi maiores sed animi nostrum.</p>
            <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Facere, voluptates dolorem, cum ratione reiciendis accusantium amet placeat, beatae et exercitationem asperiores sed quam omnis voluptatibus reprehenderit sequi aliquid! Saepe, sunt nulla inventore porro esse expedita magnam quod blanditiis enim at optio omnis animi quia consequuntur placeat delectus iure corrupti architecto!
            </p>
        </div>
        <div class="relative ">
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
    font-size: 17px;
    color: grey;
}
p:last-child{
    font-size: 13px;
}
.ab-card{
    width: 50%;
    padding-right: 30px;
}
h3{
    color: #85b680;
    padding: 25px 0;
}
.inputcard{
    box-shadow: 0px 0px 10px 1px #888888;
    position: absolute;
    border-radius: 10px;
    top: -30px;
    background-color: white;
    width: 450px;
    padding-bottom: 20px;
}
.relative{
    position: relative;
}
div.inputcard p{
    font-size: 13px;
    padding: 0 29px;
}
input{
    width: 90%;
    background-color: #F7F7F7;
    border: 1px solid #e5e8eb;
    margin-top: 15px;
    font-size: 10px;
    padding: 10px 8px;
}
span{
    background-color: #7ABC64;
    color: white;
    padding: 8px 20px;
    border-radius: 15px;
    text-transform: uppercase;
    font-size: 13px;
}
.giu{
    padding-bottom: 100px;
}
</style>