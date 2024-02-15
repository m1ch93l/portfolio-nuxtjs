<template>
    <div>Projects</div>

    <section v-if="pending">Loading...</section>
    <section v-else-if="error">Something went wrong...</section>
    <section v-else>Here we display the repos!</section>
</template>

<script setup>
const request = 'https://api.github.com/users/piotr-jura-udemy/repos';
const { error, pending, data } = await useFetch(request);
</script>