<template>
  <div id="app">
     <Header></Header>
    <router-view/>
  </div>
</template>

<script>
import Header from '@/components/Header'
export default {
  name: 'App',
  data(){

  },
  components:{
    Header,
  }
}
</script>

<style>

</style>
