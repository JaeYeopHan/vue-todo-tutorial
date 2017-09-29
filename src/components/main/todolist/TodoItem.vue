<template>
<li class="todo">
    <div class="view">
        <input class="toggle" type="checkbox">
        <!-- <label>title</label> -->
        <button class="destroy"></button>
    </div>
    <input class="edit" type="text">
</li>
</template>
<script>
export default {
    name: "todo-item",
}
</script>
