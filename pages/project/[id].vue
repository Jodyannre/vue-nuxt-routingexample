<template>
    <NuxtLayout name="projects">
        <h1> Project id: {{ projectId }}</h1>
    </NuxtLayout>
</template>
  
<script lang="ts" setup>
    import { ref } from 'vue';
    /* Layout de forma programatica */
    definePageMeta({
        title: 'Project',
        description: 'Project page',
        layout: 'projects'
    });
    const router = useRoute();
    const projectId = ref(router.params.id);

</script>
  
<style scoped>
</style>
  