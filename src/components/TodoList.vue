<script lang="ts">
import TodoListItem from "./TodoListItem.vue";

export default {
  props: {},
  components: {
    TodoListItem,
  },
};
</script>

<template>
  <h1 class="text-center bg-color">Todo List</h1>
  <TodoListItem />
</template>
