<template>
    <header>
            <input type="text" name="todoInput" id="todoInput" placeholder="What to do?" />
            <button class="submit" id="createTodo">+</button>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

style with <style lang="scss" scoped>
    header {
        display: flex;
        input {
            flex: 1;
            height: 35px;
            box-sizing: border-box;
        }

        .submit {
            width: 50px;
            height: 35px;
        }
    }
</style>