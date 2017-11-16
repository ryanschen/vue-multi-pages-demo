<template>
  <div class="page1">
      <a href="../views/page2.html">page2</a>
      <a href="../views/page3.html">page3</a>
      <hello-world></hello-world>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
    components: {
      HelloWorld
    }
}
</script>

<style scoped>
.page1 a{
  color: red;
}
</style>
