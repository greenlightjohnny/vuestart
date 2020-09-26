<template>
  <div>
    <div v-for="todo in todos" :key="todo.id">
      <TodoItem />
    </div>
  </div>
</template>
<script>
import TodoItem from "./TodoItem.vue";

export default {
  name: "Todos",
  props: ["todos"],
  components: {
    TodoItem,
  },
};
</script>
<style lang="scss" scoped>
</style>