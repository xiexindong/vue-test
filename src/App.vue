<template>
    <div>
   {{greeting}} world!
    <Header/>

  
  </div>   
</template>

<script>
import Header from './components/header/header.vue'

  export default{
    data() {
      return {
        greeting:"xxd"
      }
    },
    components:{
      Header
    }
  }
</script>


<style scoped>
  p{
    font-size: 2em;
    text-align: center;
  }
</style>