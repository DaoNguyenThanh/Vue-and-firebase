<template>
  <div id="app">
    <div v-if="isShow">Lap trinh vien TV</div>
    <button @click="isShow=!isShow">
     <span v-if="isShow">Ẩn</span>
     <span v-else>Hiện</span>
    </button>    
  </div>
</template>
 
<script>
 
 
export default {
  data(){
    return{
      isShow: true
      } 
    }
  }
 
</script>
 
<style>
 
</style>