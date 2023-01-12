<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';

defineProps({
    canLogin: Boolean,
    canRegister: Boolean,
    laravelVersion: String,
    phpVersion: String,
});
</script>

<template>
    <Head title="Bem vindo" />
    <div>
        <h1>Bem Vindo Inertia App.</h1>
        <p>Laravel v{{ laravelVersion }} (PHP v{{ phpVersion }})</p>
    </div>
</template>