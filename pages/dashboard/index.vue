<script setup lang="ts">
definePageMeta({ middleware: ["auth"] });
const loading = ref(false)
</script>

<template>
  <NuxtLayout name="app-layout">
    <Head>
      <Title>Home</Title>
    </Head>

    <!-- <template #header>
      <h2 class="font-semibold text-xl text-gray-800 leading-tight">
        Home
      </h2>
    </template> -->

    <div class="my-12">
      <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
        <div class="bg-white overflow-hidden shadow-sm sm:rounded-lg">
          <div class="p-6 bg-white border-b border-gray-200">
            You're logged in!
          </div>
        </div>
      </div>
    </div>
  </NuxtLayout>
</template>
