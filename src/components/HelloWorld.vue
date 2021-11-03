<script setup lang="ts">
defineProps<{
  msg: boolean
}>()
</script>

<template>
  <h4>msg: {{ msg ? 'msg true' : 'msg false' }}</h4>
</template>
