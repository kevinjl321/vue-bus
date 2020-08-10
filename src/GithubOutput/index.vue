<template>
    <div>
        <p v-if="currentUsername == null">
            Enter a username above to see their GitHub data
        </p>
        <p v-else>
            Below are the results for {{ currentUsername }}:
            <github-user-data :data="githubData[currentUsername]"></github-user-data>
        </p>
    </div>
</template>
<script src="./script.js"></script>
<style scoped src="./style.css"></style>