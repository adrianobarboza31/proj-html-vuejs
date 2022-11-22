<template>
  <div>
    <Section1Component/>
    <Section2Component/>
    <Section3Component/>
    <Section4Component/>
    <Section5Component/>
  </div>
</template>

<script>
import Section5Component from './Section5Component.vue';
import Section3Component from './Section3Component.vue';
import Section1Component from './Section1Component.vue';
import Section2Component from './Section2Component.vue';
import Section4Component from './Section4Component.vue';
  export default {
    components:{
      Section1Component,
      Section2Component,
      Section3Component,
      Section4Component,
      Section5Component
    }
  }
</script>

<style lang="scss" scoped>

</style>