<template>
  <div id="app">
    <div v-show="isShow">
    <h1>Lap Trinh Vien TV</h1>
    </div>
    <button @click="isShow = ! isShow">An/Hien</button>
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

