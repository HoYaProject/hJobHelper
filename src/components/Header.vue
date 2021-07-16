<template>
  <header>
    <h1 class="my-4 text-5xl text-green-500 font-bold">{{ title }}</h1>
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Header",
  props: {
    title: String,
  },
});
</script>
