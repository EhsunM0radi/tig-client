<script setup lang="ts">
definePageMeta({ middleware: ["auth"] });
const loading = ref(false)
</script>

<template>
  <NuxtLayout name="app-layout">
    <Head>
      <Title>Sprints</Title>
    </Head>

    
    <div>
        sprints
    </div>
  </NuxtLayout>
</template>