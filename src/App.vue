<template>
  <div id="app">
    <Todo />

    <!-- <todo-app></todo-app> -->
  </div>
</template>

<script>
import Todo from "./components/Todo.vue";
// import TodoApp from "./components/TodoApp.vue";

export default {
  name: "App",
  components: {
    // TodoApp,
    Todo,
  },
};
</script>