<template>
  <div>
    <Heador></Heador>
    <Mslider></Mslider>
    <Ada></Ada>
    <Choice></Choice>
    <Footor></Footor>
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
export default {
  components: {
    Heador,
    Footor,
    Navbar,
    Mslider,
    Ada,
    Choice
  }
};
</script>
