<script setup>

import { Head } from '@inertiajs/vue3';
import Frontend from '@/Layouts/Frontend.vue';
import Hero from "@/Components/Frontend/Hero.vue";
import Promote from "@/Components/Frontend/Promote.vue";
import About from "@/Components/Frontend/About.vue";
import Skills from "@/Components/Frontend/Skills.vue";


defineProps({
  skills: Object,
  projects: Object,
});

</script>

<template>
    <Head title="Home" />
    <Frontend/>
    <!-- Hero primary -->
    <Hero />
    <!-- Promote tail-100 -->
    <Promote />
    <!-- About secondary -->
    <About />
    <!-- Skills tail-100 -->
    <Skills :skills="skills" />
</template>

<style>
</style>
