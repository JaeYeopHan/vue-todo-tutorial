<template>
<section class="main">
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
