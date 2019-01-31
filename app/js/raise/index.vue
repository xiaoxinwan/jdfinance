<template>
  <div>
    <Heador></Heador>
    <Rslider></Rslider>
    <Daily></Daily>
    <In></In>
    <More></More>
    <Footor></Footor>
    <Navbar></Navbar>
  </div>
</template>

<script>
  import Heador from '../public/header.vue';
  import Footor from '../public/footer.vue';
  import Navbar from '../public/navbar.vue';
  import Rslider from './rslider.vue'
  import Daily from './daily.vue';
  import In from './in.vue';
  import More from './more.vue';
  export default {
    components:{
      Heador,Footor,Navbar,Rslider,Daily,In,More
    }
  }
</script>

