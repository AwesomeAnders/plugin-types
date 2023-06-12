<script setup>
const newQuery = { query: "query" };

const router = useRouter();

router.replace({ query: newQuery });
</script>

<template>
  <NuxtLayout>
    current query {{ $router.currentRoute.value.query }}
  </NuxtLayout>
</template>
