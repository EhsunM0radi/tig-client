<script setup lang="ts">
definePageMeta({ middleware: ["auth"] });
const loading = ref(false)
</script>

<template>
  <NuxtLayout name="app-layout">
    <Head>
      <Title>Tasks</Title>
    </Head>

    
    <div>
        tasks
    </div>
  </NuxtLayout>
</template>