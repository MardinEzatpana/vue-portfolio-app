<script setup>
import Header from "@/Components/Frontend/Header.vue";
</script>
<template>
  <div class="bg-slate-200 dark:bg-slate-900">
    <!-- Header -->
    <Header />
    <main >
      <slot />
    </main>
    <!-- Footer -->
  </div>
</template>
