<template>
 <HeaderComponent/>
 <MainComponent/>
 <FooterComponent/>
</template>

<script>
import axios from 'axios';
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import MainComponent from './components/MainComponent.vue';
  export default {
    components:{
      HeaderComponent,
      FooterComponent,
      MainComponent
    }
  }
</script>

<style lang="scss" scoped>

</style>