<template>
  <div>
    <Heador></Heador>
    <Mslider></Mslider>
    <Ada></Ada>
    <Choice></Choice>
    <Adb></Adb>
    <Money></Money>
    <Adc></Adc>
    <Footor cname='mfooter'></Footor>
    <Navbar></Navbar>
  </div>
</template>

<script>
import Heador from "../public/header.vue";
import Footor from "../public/footer.vue";
import Navbar from "../public/navbar.vue";
import Mslider from './mslider.vue';
import Ada from './ada.vue';
import Choice from './choice.vue';
import Adb from './adb.vue';
import Money from './money.vue';
import Adc from './adc.vue';

export default {
  components: {
    Heador,
    Footor,
    Navbar,
    Mslider,
    Ada,
    Choice,
    Adb,
    Money,
    Adc
  }
};
</script>
<style lang="scss">
  .mfooter{
    margin-top: 0!important;
    ul{
      li:first-child{
        display: none;
      }
    }
  }
</style>
