<template>
  <div>

    <app-header></app-header>
    <router-view></router-view>
  
  </div>
</template>

<script>

import Header from "./Components/Header.vue"

import products from "../public/products"

export default {
  components: {
    appHeader: Header
  }
  
   
  
     

}
</script>

