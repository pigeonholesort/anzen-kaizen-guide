<template>
  <span id="nextTodo">次のTODO: {{nextTodoText}}</span>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  props: {
    nextTodoText: { type: String }
  }
});
</script>

<style scoped>
span {
  font-weight: bold;
  font-size: 1.2rem;
}
</style>