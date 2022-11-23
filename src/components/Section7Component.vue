<template>
    <div class="sfondo d-flex align-items-center" >
        <div class="ab-container text-center ">
            <h2>Sign up to our Newsletter</h2>
            <br>
            <input type="text">
            <br>
            <span>subscribe</span>
            <p class="mt-5">We do not share your data with anybody, and only use it for its intended purpose</p>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.sfondo{
    background-image: url('/img/newsletter_background.jpg');
    background-size:cover;
    height: 400px;

}
input{
    width: 100%;
    padding: 10px 0;
    margin-bottom: 40px;
    margin-top: 20px;
    border: 2px solid #e5e8eb;
}
span{
    background-color: #7ABC64;
    padding: 10px 250px;
    border-radius: 40px;
    color: white;
    text-transform: uppercase;
    font-weight: 600;
    transition: 0.3s;
}
span:hover{
    filter: contrast(1.50);
}
p{
    font-size: 13px;
    color: gray;
}
</style>