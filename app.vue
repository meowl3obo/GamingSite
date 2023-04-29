<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script lang="ts" setup>
const runtimeConfig = useRuntimeConfig()
console.log(runtimeConfig.public)
</script>