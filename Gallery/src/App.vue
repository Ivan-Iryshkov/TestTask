<script setup lang="ts"></script>

<template>
  <header class="header">
    <div class="header__links">
      <a class="icon__FWT" href="https://framework.team/">
        <img src="./assets/FWT.svg" alt="FWT" />
      </a>
      <button class="toogle-theme-btn" type="button">
        <img src="./assets/sun.svg" alt="Toogle theme" />
      </button>
    </div>
    <nav class="filter__inputs">
      <label for="">
        <input class="input" type="text" placeholder="Name" />
        <select class="input" name="Author" id="Author">
          <option value="Author">Author</option>
        </select>
        <select name="Location" id="Location">
          <option value="Location">Location</option>
        </select>
        <select name="Created" id="Created">
          <option value="Created">Created</option>
        </select>
      </label>
    </nav>
  </header>
  <main>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/ThePersistenceOfMemory1366.jpg" alt="The Persistence Of Memory" />
      <span class="desc-name">The Persistence Of Memory</span>
    </picture>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/TheStarryNight1366.jpg" alt="The Starry Night" />
    </picture>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/TheFlyingCarpet1366.jpg" alt="The Flying Carpet" />
    </picture>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/ImpressionSunrise1366.jpg" alt="Impression Sunrise" />
    </picture>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/TheNightWatch1366.jpg" alt="The Night Watch" />
    </picture>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/MontSainteVictoire1366.jpg" alt="Mont Sainte Victoire" />
    </picture>
    <picture class="painting">
      <img
        class="painting__img"
        src="./assets/img/StillLifeWithCompoteAndGlass1366.jpg"
        alt="Still Life With Compote And Glass"
      />
    </picture>
    <picture class="painting">
      <img
        class="painting__img"
        src="./assets/img/ArragementinGreyAndBlack1366.jpg"
        alt="Arragementin Grey And Black"
      />
    </picture>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/TheLastSupper1366.jpg" alt="The Last Supper" />
    </picture>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/TheCourseOfEmpire1366.jpg" alt="The Course Of Empire" />
    </picture>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/TheBlackSea1366.jpg" alt="The Black Sea" />
    </picture>
    <picture class="painting">
      <img class="painting__img" src="./assets/img/TheSwing1366.jpg" alt="The Swing" />
    </picture>
  </main>
</template>

<style scoped></style>
