<template>
  <Header title="About" />
  <div class="about">
    <h1>This is an about page</h1>
  </div>
  <Footer />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default defineComponent({
  name: "About",
  components: {
    Header,
    Footer,
  },
});
</script>
