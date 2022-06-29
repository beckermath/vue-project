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
  <h1>Todo List</h1>
  <TodoListItem />
</template>
