<template>
  <Header title="Home" />
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" class="mx-auto" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
  <Footer />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default defineComponent({
  name: "Home",
  Header,
  components: {
    Header,
    HelloWorld,
    Footer,
  },
});
</script>
