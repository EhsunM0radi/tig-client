<script setup lang="ts">
definePageMeta({ middleware: ["auth"] });
const loading = ref(false)
</script>

<template>
  <NuxtLayout name="app-layout">
    <Head>
      <Title>Calendar</Title>
    </Head>

    
    <div>
        calendar
    </div>
  </NuxtLayout>
</template>