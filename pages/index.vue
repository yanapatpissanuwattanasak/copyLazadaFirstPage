<template>
<div class ="div">
  <div class = "div-header-ads"></div>
  <div class = "div-default">
    <Header></Header>
    <Banner></Banner>
    
  </div>
  <!-- <Banner></Banner> -->
  
</div>
  
  
</template>

<script lang="ts">
import Vue from 'vue'
import Header from '~/components/Header.vue'
import Banner from '../components/Banner.vue'


export default Vue.extend({
    name: "IndexPage",
    components: { Header, Banner }
})
</script>

<style lang="css">
  .div-header-ads {
    height: 80px;
    min-width: 1188;
    background-color: rgb(124, 250, 187);
  }

  
</style>


