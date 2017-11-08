<template>
<li :id="todoId" class="todo">
    <div class="view">
        <input :checked="todoStatus" class="toggle" type="checkbox">
        <label>{{todoTitle}}</label>
        <button class="destroy"></button>
    </div>
    <input class="edit" type="text">
</li>
</template>
<script>
export default {
    name: "todo-item",
    props: ["item"],
    data: function() {
        return {
            todoTitle: this.item.title,
            todoId: this.item.id,
            todoStatus: this.item.done,
        };
    },
}
</script>
