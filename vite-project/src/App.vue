
<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/questions.vue'
import questions from './components/questions.vue';
const answers = [
  {
    songName: 'The Yodel Song'
  },
  {
    songName: 'Aberdeen'
  },
  {
    songName: '19888 Capitol Lake Jam Commercial'
  },
  {
    songName: 'Burn The Rain'
  },
  {
    songName: 'Do Re Mi - Meledy'
  },
  {
    songName: 'Scream'
  },
  {
    songName: 'Sappy - Early Demo'
  },
  {
    songName: 'And I Love Her'
  },
  {
    songName: 'Desire'
  },
  {
    songName: 'Letters To Frances'
  },
  {
    songName: 'Underground Celebritism'
  },
  {
    songName: "Change Me / Burn My Britches / Something In The Way - Early Demo"
  },
  {
    songName: 'Reverb Expierement'
  },
  {
    songName: 'Beans'
  },
  {
    songName: 'The Happy Guitar'
  },
  {
    songName: "Been A Son - Early Demo"
  },
 ]
 console.log(answers)
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
