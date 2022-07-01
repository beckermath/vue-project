<script lang="ts">
import TodoListItem from "./TodoListItem.vue";
import mockTodos from "../data/todos.json";

export default {
  components: {
    TodoListItem,
  },
  data: () => {
    return {
      todos: mockTodos,
    };
  },
};
</script>

<template>
  <h1 class="p-10 text-xl font-bold text-center">Todo List</h1>
  <ul>
    <li v-for="todo in todos" :key="todo.id">
      <TodoListItem :todo="todo" :key="todo.id" />
    </li>
  </ul>
</template>
