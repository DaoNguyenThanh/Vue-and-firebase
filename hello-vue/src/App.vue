
<template>
  <div id="app">
    <hello-world :citiesRef="citiesRef" />
  </div>
</template>
 
<script>
import HelloWorld from './components/HelloWorld.vue'
import db from './firebase/firebaseInit'
 
export default {
  components: { HelloWorld },
  data(){
    return{
      citiesRef: {}
    }
  },
  created(){
    this.citiesRef = db.collection("cities");
  },
  beforeCreated(){

  },
  methods: {
    
  },
  watch: {
    
  }
}
</script>
 
<style>
</style>
