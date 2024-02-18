<template>
    <article c>
        <ContentDoc />
    </article>
</template>

<script setup>
const route = useRoute()
console.log(route.params.slug)
</script>