<template>
    <h2>Hello {{ name }}</h2>
    <h2 v-text="name"></h2>
</template>

<script>
export default {
    name: "App",
    data() {
        return {
            name: "Bob",
        };
    },
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
