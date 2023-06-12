<script setup>
definePageMeta({
  layout: false,
});
const newQuery = { query: "query" };

const router = useRouter();

router.replace({ query: newQuery });
</script>

<template>current query: {{ router.currentRoute.value.query }}</template>
