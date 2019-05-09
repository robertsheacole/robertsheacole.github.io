<template>
  <div class="home">
    <h1>Welcome to SheaCole.com!</h1>
    <img alt="Vue logo" src="../assets/family_pic.jpg">
    <HelloWorld/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>
  img {
    max-height: 300px;
  }
</style>
