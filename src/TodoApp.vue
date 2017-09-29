<template>
<div id="todolistapp">
    <section class="todoapp">
        <todo-header></todo-header>
        <main-container></main-container>
        <todo-footer></todo-footer>
    </section>
    <todo-info></todo-info>
</div>
</template>

<script>
import TodoHeader from "./components/header/Header.vue";
import MainContainer from "./components/main/MainContainer.vue";
import TodoFooter from "./components/footer/Footer.vue";
import TodoInfo from "./components/info/Info.vue";

export default {
    name: 'todo-list',
    components: {
        TodoHeader,
        MainContainer,
        TodoFooter,
        TodoInfo,
    },
}
</script>

<style>
</style>
