<script setup>
const newQuery = { index: "index" };

const router = useRouter();

router.replace({ query: newQuery });
</script>

<template>current query: {{ router.currentRoute.value.query }}</template>
