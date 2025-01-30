<template>
    <div class="home">
        <video autoplay loop muted class="background-video">
            <source src="@/assets/videos/party-video.mp4" type="video/mp4" />
         </video>
  
      <div class="content">
        <h1>Välkommen till Festappen! 🎉</h1>
        <p>Välj ett spel att börja med:</p>
        <div class="game-list">
          <div class="game-item">
            <QuizGame />
          </div>
          <div class="game-item">
            <DrinkingGame />
          </div>
          <div class="game-item">
            <PartyGame />
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup lang="ts">
  import QuizGame from '@/components/games/QuizGame/QuizGame.vue';
  import DrinkingGame from '@/components/games/NeverHaveIEver/NeverHaveIEver.vue';
  import PartyGame from '@/components/games/SpinTheBottle/SpinTheBottle.vue';
  </script>
  
  <style src="./HomeView.css" scoped></style> 
  