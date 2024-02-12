
<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/questions.vue'
import questions from './components/questions.vue';
</script>

<template>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <div>
    <form action="submit">
    <questions />
  </form>
    </div>
</body>
</html>
</template>

<style>
h1{
  font-size: 3rem;
}
</style>
