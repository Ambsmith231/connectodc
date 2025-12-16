<script setup>
import NavBar from "@/components/NavBar.vue";
import hero from "@/components/hero.vue";
import foot from "@/components/foot.vue";
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <main class="flex-grow">
      <NavBar />
      <hero />
    </main>
    <foot />
  </div>
</template>
