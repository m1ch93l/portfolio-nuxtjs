<template>
    <div class="container mx-auto max-w-2xl">
        <header class="flex justify-between items-center mt-5">
            <div>
                <nuxt-link to="/" class="text-xl font-semibold p-2 hover:bg-gray-200">Michael B. Bañaria</nuxt-link>
            </div>

            <Menu />
        </header>

        <main class="mt-10">
            <slot />
        </main>

    </div>
</template>

<script setup>
useHead({

})
</script>