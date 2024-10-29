<template>
  <div>{{ message }}</div>
</template>

<script lang="ts" setup>
const { data: message } = await useFetch("/api/demo");
</script>

<style></style>
