<template>
    <div class="img-sfondo">
        <div class="ab-container d-flex justify-content-between align-items-center centro">
            <div>
                <h2>Start Learning to Drive Today</h2>
                <p><strong>Give us a call to schedule your first driving lesson</strong></p>
            </div>
            <div class="pe-5">
                <i class="fa-solid fa-phone"></i>  1-800-555-555
            </div>
        </div>
    </div>
</template>

<script>
    export default {
    }
</script>

<style lang="scss" scoped>
.img-sfondo{
    background-image: url('/img/horizontal-cta-background.jpg');
    background-size: cover;
    color: white;
}
div.pe-5{
    font-size: 35px;
}
.centro{
    height: 270px;
}
h2{
    font-size: 40px;
}
strong{
    font-size: 20px;
}
i{
    padding-right: 30px;
}
</style>