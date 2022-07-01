<script lang="ts">
export default {
  props: {
    todo: Object,
  },
};
</script>
<template>
  <div class="flex justify-center p-1 text-lg align-middle">
    <input class="p-2" type="checkbox" />
    <p class="p-2">{{ todo.title }}</p>
    <button class="p-2">x</button>
  </div>
</template>
