<template>
  <div class="page2">
      <a href="../views/page1.html">page1</a>
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
.page2 a{
  color: yellow;
}
</style>