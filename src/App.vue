<template>
    <h2 v-bind:id="headingID">Heading</h2>
    <button v-bind:disabled="isDisable">Bind</button>
</template>

<script>
export default {
    name: "App",
    data() {
        return {
            headingID: "heading",
            isDisable: true,
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
