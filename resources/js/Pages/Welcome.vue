<script setup lang="ts">
import {ref} from 'vue';
import {Link} from '@inertiajs/vue3';

const greeting = ref('Welcome to  Your Laravel + Vue.js + TypeScript App!');

</script>

<template>
    <h1>{{ greeting }}</h1>
    <Link href="/about">Go to About page</Link>
</template>

<style scoped>

</style>
