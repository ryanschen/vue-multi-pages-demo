<template>
  <div class="page3">
      <a href="../views/page1.html">page1</a>
      <a href="../views/page2.html">page2</a>
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
.page3 a{
  color: green;
}
</style>