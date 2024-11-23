<template>
    <div>
        <nav>
            <ul>
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="contact">Contact</NuxtLink></li>
                <li><Nuxt-link to="about">About</nuxt-link></li>
                <li><Nuxt-link to="services">Services</nuxt-link></li>
            </ul>
        </nav>
    <slot />
    </div>
</template>
  
<script lang="ts" setup>

</script>
  
<style scoped>
</style>
  