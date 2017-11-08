<template>
<ul class="todo-list">
    <todo-item
        v-for="item in todoitems"
        v-bind:item="item"
        v-bind:key="item.id"
    >
    </todo-item>
</ul>
</template>
<script>
import TodoItem from "./TodoItem.vue";

export default {
    name: "todo-list-container",
    components: {
        TodoItem,
    },
    data: function() {
        return {
            todoitems: [
                {id: 0, title: "Study Vuejs", done: true},
                {id: 1, title: "Study Reactjs", done: false},
                {id: 2, title: "Study Angular", done: false},
            ],
        };
    }
}
</script>
