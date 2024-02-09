<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
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
    <h1>Which Song from "Montage of HECK" are you?</h1>
  </div>
  <div class="quiz">
  
  <h2 class="quiz-question">Q1: Do You Like spoken word songs?</h2>
  <ul data-quiz-question="1">
    <input type='checkbox' class="quiz-answer" data-quiz-answer="Y">YES</input>
    <input type="checkbox" class="quiz-answer" data-quiz-answer="N">NO</input>
  </ul>
  
  
  <h2 class="quiz-question">Q2: Do you like Nirvana's music style?</h2>
  <ul data-quiz-question="2">
    <input type="checkbox" class="quiz-answer" data-quiz-answer="Y">YES</input>
    <input type="checkbox" class="quiz-answer" data-quiz-answer="N">NO</input>
  </ul>
  
  <h2 class="quiz-question">Q3: Are You Sad?</h2>
  <ul data-quiz-question="3">
    <input type="checkbox" class="quiz-answer" data-quiz-answer="Y">YES</input>
    <input type="checkbox" class="quiz-answer" data-quiz-answer="N">NO</input>
  </ul>
  
  <h2 class="quiz-question">Q4: Are You a Fan of Yodeling?</h2>
  <ul data-quiz-question="4">
    <input type="checkbox" class="quiz-answer" data-quiz-answer="Y">YES</input>
    <input type="checkbox" class="quiz-answer" data-quiz-answer="N">NO</input>
  </ul>
</div>
</body>
</html>
</template>

<style>
h1{
  font-size: 3rem;
}
</style>
