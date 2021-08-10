<template>
  <div id="app">
    <div id="nav">
      <!-- <router-link to="/home" tag="button">首页 </router-link>
      <router-link to="/about" tag="button">关于</router-link> -->
      <button @click="linktohome">首页</button>
      <button @click="linktoabout">关于</button>
    </div>
      <router-view/>
  </div>
</template>


<script>
export default {
  name:'App',
  methods :{
      linktohome(){
        this.$router.push('/home')
      },
      linktoabout(){
         this.$router.push('/about')
      }
  }

}
</script>

<style>

</style>