<template>
    <form v-on:submit.prevent="onSubmit">
        <input type="text" v-model="username" placeholder="Enter a github username here" />
        <button type="submit">Go!</button>
    </form>
</template>

<script src="./script.js"></script>
<style scoped src="./style.css"></style>