<template>
<ul class="todo-list">
    <todo-item></todo-item>
</ul>
</template>
<script>
import TodoItem from "./TodoItem.vue";

export default {
    name: "todo-list-container",
    components: {
        TodoItem,
    }
}
</script>
