<script setup lang="ts">
defineProps<{
  message: string;
  count: number;
}>();
</script>

<template>
  <main>
    <h2>This is ChildComp</h2>
    <p>{{ message }}{{ count }}</p>
  </main>
</template>

<style scoped lang="scss">
main {
  h2 {
    font-size: 30px;
  }

  p {
    font-size: 16px;
  }
}
</style>
