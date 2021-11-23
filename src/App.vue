<template>
    <h2>Hello <span v-html="name"></span></h2>
    <div v-html="name"></div>
</template>

<script>
export default {
    name: "App",
    data() {
        return {
            name: "<b>Bob</b>",
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
