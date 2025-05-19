<script setup lang="ts">
import { ref } from "vue";
import ChildComp from "@components/ChildComp.vue";

const test = ref("This is Vue.js");
</script>

<template>
  <h1>{{ test }}</h1>
  <ChildComp
    message="これはWebpackでVue.jsを使用するためのフォーマットです。"
    :count="123"
  />
</template>

<style scoped lang="scss"></style>
