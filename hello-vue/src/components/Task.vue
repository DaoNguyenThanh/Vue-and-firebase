<template>
  <div id="task">
    <span>{{ taskData.content }}</span>
  </div>
</template>
 
<script>
 
 
export default {
   props: ['taskData'],
   data(){
       return{
           content: 'ABC'
       }
   }
}
</script>
 
<style scoped>

</style>
