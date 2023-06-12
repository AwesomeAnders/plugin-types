<script setup lang="ts">
definePageMeta({
  layout: false,
});
const newQuery = { test: "test" };

const router = useRouter();

router.replace({ query: newQuery });
</script>

<template>
  <NuxtLayout name="filter-layout">
    current query {{ $router.currentRoute.value.query }}
  </NuxtLayout>
</template>
