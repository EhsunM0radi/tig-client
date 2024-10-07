<script setup lang="ts">
definePageMeta({ middleware: ["auth"] });
const loading = ref(false)
</script>

<template>
  <NuxtLayout name="app-layout">
    <Head>
      <Title>Teams</Title>
    </Head>

    
    <div>
        teams
    </div>
  </NuxtLayout>
</template>