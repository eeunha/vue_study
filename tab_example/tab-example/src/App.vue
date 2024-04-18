<!-- App.vue -->
<template>
  <div id="app">
    <TodoHeader></TodoHeader>
    <TodoTabs></TodoTabs>
    <Tabtab_></Tabtab_>
    <TodoInput></TodoInput>
    <TodoList></TodoList>
    <TodoFooter></TodoFooter>
    <p>test</p>
  </div>
</template>

<script>
import TodoHeader from "./components/TodoHeader.vue";
import TodoTabs from "./components/TodoTabs.vue";
import TodoInput from "./components/TodoInput.vue";
import TodoList from "./components/TodoList.vue";
import TodoFooter from "./components/TodoFooter.vue";
import Tabtab_ from "./components/Tabtab_.vue";

export default {
  name: "App",
  components: {
    TodoHeader: TodoHeader,
    TodoTabs: TodoTabs,
    TodoInput: TodoInput,
    TodoList: TodoList,
    TodoFooter: TodoFooter,
    Tabtab_: Tabtab_,
  },
};
</script>

<style></style>
