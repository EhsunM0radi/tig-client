<script setup lang="ts">
definePageMeta({ middleware: ["auth"] });
const loading = ref(false)
</script>

<template>
  <NuxtLayout name="app-layout">
    <Head>
      <Title>Market</Title>
    </Head>

    
    <div>
        market
    </div>
  </NuxtLayout>
</template>