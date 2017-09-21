<template>
<div id="todolistapp">
    <section class="todoapp">
			<!-- <header class="header"> -->
				<!-- <h1>todos</h1> -->
				<!-- <input class="new-todo" autofocus autocomplete="off" placeholder="What needs to be done?"> -->
			<!-- </header> -->
        <todo-header></todo-header>
        <section class="main">
            <input class="toggle-all" type="checkbox">
            <ul class="todo-list">
                <li class="todo">
                    <div class="view">
                        <input class="toggle" type="checkbox">
                        <!-- <label>title</label> -->
                        <button class="destroy"></button>
                    </div>
                    <input class="edit" type="text">
                </li>
            </ul>
        </section>
        <footer class="footer">
            <span class="todo-count">
                <strong></strong>0 left
            </span>
            <ul class="filters">
                <li><a href="#/all">All</a></li>
                <li><a href="#/active">Active</a></li>
                <li><a href="#/completed">Completed</a></li>
            </ul>
            <button class="clear-completed">
                Clear completed
            </button>
        </footer>
    </section>
    <footer class="info">
        <p>Double-click to edit a todo</p>
        <p>Written by <a href="http://evanyou.me">Jbee</a></p>
        <p>Part of <a href="http://todomvc.com">TodoMVC</a></p>
    </footer>
</div>
</template>

<script>
import TodoHeader from "./components/Header.vue";

export default {
    name: 'todo-list',
    components: {
        TodoHeader
    },
}
</script>

<style>
</style>
