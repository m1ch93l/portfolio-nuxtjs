<template>
    <div>
        <nav>
            <ul>
                <li>
                    <nuxt-link to="/">Main</nuxt-link>
                </li>
                <li>
                    <nuxt-link to="/about">About</nuxt-link>
                </li>
            </ul>
        </nav>
        <slot />
    </div>
</template>