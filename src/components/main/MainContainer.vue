<template>
<section class="main">
    <input class="toggle-all" type="checkbox">
    <todo-list-container></todo-list-container>
</section>
</template>
<script>
import TodoListContainer from "./todolist/TodoListContainer.vue";

export default {
    name: "main-container",
    components: {
        TodoListContainer,
    }
}
</script>
