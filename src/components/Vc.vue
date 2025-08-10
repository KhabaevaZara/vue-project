<template>
  <div>
    <div class="game-modal">
      <div class="content">
        <img src="/vue-project/public/" alt="gif">
        <h6></h6>
        <p><b></b></p>
        <button class="play-again">Play again</button>
      </div>
    </div>

    <div class="container">
      <div class="hangman-box">
        <img src="/vue-project/public/" alt="hangman">
        <h6>Hangman Game</h6>
      </div>
      <div class="game-box">
        <ul class="word-display"></ul>
        <h6 class="hint-text">
          Hint:
          <b>.</b>
        </h6>
        <h6 class="guesses-text">
          Incorrect guesses:
          <b>0/6</b>
        </h6>
        <div class="keyboard"></div>
      </div>
    </div>
  </div>
</template>