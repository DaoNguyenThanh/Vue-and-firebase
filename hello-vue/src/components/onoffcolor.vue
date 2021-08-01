<template>
  <div id="app">
    <h1 :class="{daChon: selected}">Lap Trinh Vien TV</h1>
    <button @click="selected = !selected">CLick</button>
  </div>
</template>
 
<script>
 
 
export default {
  
  data(){
    return{
      selected :true
    }
  }
}
</script>
 
<style>
.daChon{
  color: red;
}
</style>