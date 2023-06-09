<script setup lang="ts">
const { $hello } = useNuxtApp();
</script>
<template>
  <div>
    {{ $hello("awdawd") }}
    <NuxtWelcome />
  </div>
</template>
