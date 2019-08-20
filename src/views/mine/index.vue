<template>
  <div id="mine">
    <Header title="我的喵喵"/>
    <div id="content">
      <Login />
    </div>
    <TabBar/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import TabBar from '@/components/TabBar.vue'
import Login from '@/components/Login.vue'
export default {
  name: 'Mine',
  components: {
    Header,
    TabBar,
    Login
  }
}
</script>

<style scoped>

</style>
