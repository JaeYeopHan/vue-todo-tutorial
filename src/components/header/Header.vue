<template>
<header class="header">
    <h1>{{title}}</h1>
    <input class="new-todo" autofocus autocomplete="off" placeholder="What needs to be done?">
</header>
</template>
<script>
export default {
    name: "todo-header",
    data: function() {
        return { title: "todos"}
    }
}
</script>
