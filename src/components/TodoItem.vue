<template>
  <div>
    <p>Todo Item</p>
  </div>
</template>

<script>
export default {
  name: "TodoItem",
};
</script>

<style lang="scss" scoped>
.todo-item {
  background: #fff;
  padding: 15px;
  border-bottom: #ccc dotted;
}

.is-complete {
  text-decoration: line-through;
}

.del {
  background: #ff0000;
  color: #fff;
  border: none;
  padding: 6px 10px;
  border-radius: 50%;
  cursor: pointer;
  float: right;
}
</style>