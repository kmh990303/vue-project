<script setup lang="ts">
const props = defineProps({
  color: String
});
</script>

<template>
  <div :style="{color: props.color}">{{ props.color || 'BLACK'}} TIRE</div>
</template>