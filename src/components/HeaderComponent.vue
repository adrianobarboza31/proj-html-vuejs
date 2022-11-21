<template>
<header>
  <NavBarComponent/>
  <HeroComponentVue/>
</header>
</template>

<script>
import NavBarComponent from './NavBarComponent.vue';
import HeroComponentVue from './HeroComponent.vue';
  export default {
    components:{
      NavBarComponent,
      HeroComponentVue
    }
  }
</script>

<style lang="scss" scoped>
header{
  background-image: url('/img/homepage-hero-background.jpg');
  background-size: cover;
}
</style>