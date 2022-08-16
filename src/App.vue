<template>
  <div id="app">
    <Header></Header>
    <div class="main">
      <router-view name="slidebar"></router-view>
      <router-view name="main"></router-view>


    </div>
  </div>
</template>
<script>
import Header from './components/Header.vue'
import postList from './components/postList.vue'

export default {
  name: 'App',
  components: {
    Header,
    postList,
  }
}

</script>


<style lang="scss">
.main {
  width: 80%;
  margin: 0 auto;
}
</style>
