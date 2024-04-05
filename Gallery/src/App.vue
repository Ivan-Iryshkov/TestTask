<script setup lang="ts"></script>

<template>
  <div class="container">
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
        <span class="desc-name">The Starry Night</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/TheFlyingCarpet1366.jpg" alt="The Flying Carpet" />
        <span class="desc-name">The Flying Carpet</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/ImpressionSunrise1366.jpg" alt="Impression Sunrise" />
        <span class="desc-name">Impression Sunrise</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/TheNightWatch1366.jpg" alt="The Night Watch" />
        <span class="desc-name">The Night Watch</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/MontSainteVictoire1366.jpg" alt="Mont Sainte Victoire" />
        <span class="desc-name">Mont Sainte Victoire</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/StillLifeWithCompoteAndGlass1366.jpg" alt="Still Life With Compote And Glass" />
        <span class="desc-name">Still Life With Compote And Glass</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/ArragementinGreyAndBlack1366.jpg" alt="Arragementin Grey And Black" />
        <span class="desc-name">Arragementin Grey And Black</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/TheLastSupper1366.jpg" alt="The Last Supper" />
        <span class="desc-name">The Last Supper</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/TheCourseOfEmpire1366.jpg" alt="The Course Of Empire" />
        <span class="desc-name">The Course Of Empire</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/TheBlackSea1366.jpg" alt="The Black Sea" />
        <span class="desc-name">The Black Sea</span>
      </picture>
      <picture class="painting">
        <img class="painting__img" src="./assets/img/TheSwing1366.jpg" alt="The Swing" />
        <span class="desc-name">The Swing</span>
      </picture>
    </main>
  </div>
</template>

<style scoped></style>
