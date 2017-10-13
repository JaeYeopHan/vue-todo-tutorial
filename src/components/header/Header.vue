<template>
<header class="header">
    <h1>{{title}}</h1>
    <input
        v-model.trim="todo"
        v-on:keyup.enter="addTodo"
        class="new-todo"
        autofocus autocomplete="off"
        placeholder="What needs to be done?"
    >
</header>
</template>
<script>
export default {
    name: "todo-header",
    data: function() {
        return {
            title: "todos",
            todo: "",
        }
    },
    methods: {
        addTodo: function() {
            console.log(this.todo);
            this.todo = "";
        }
    }
}
</script>
