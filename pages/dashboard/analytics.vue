<script setup lang="ts">
definePageMeta({ middleware: ["auth"] });
const loading = ref(false)
</script>

<template>
  <NuxtLayout name="app-layout">
    <Head>
      <Title>Analytics</Title>
    </Head>
    
    <div>
        analytics
    </div>
  </NuxtLayout>
</template>