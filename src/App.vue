<script setup>
import BaseHeader from '@/components/BaseHeader.vue'
import BaseBodyBoxes from '@/components/body/BaseBodyBoxes.vue'
</script>

<template>
  <header>

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <BaseHeader />
    <BaseBodyBoxes />
  </main>
</template>

<style scoped>

</style>
