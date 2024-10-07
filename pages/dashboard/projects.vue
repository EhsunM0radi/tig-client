<script setup lang="ts">
definePageMeta({ middleware: ["auth"] });
const loading = ref(false)
</script>

<template>
  <NuxtLayout name="app-layout">
    <Head>
      <Title>Projects</Title>
    </Head>

    
    <div>
        projects
    </div>
  </NuxtLayout>
</template>