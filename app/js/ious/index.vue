<template>
  <div>
    <Heador></Heador>
    <Islider></Islider>
    <Welfare></Welfare>
    <More></More>
    <Footor></Footor>
    <Navbar></Navbar>
  </div>
</template>

<script>
  import Heador from '../public/header.vue';
  import Footor from '../public/footer.vue';
  import Navbar from '../public/navbar.vue';
  import Islider from './islider.vue';
  import Welfare from './welfare.vue'
  import More from './more.vue';
  
  export default {
    components:{
      Heador,Footor,Navbar,Islider,Welfare,More
    }
  }
</script>

<style scoped>

</style>