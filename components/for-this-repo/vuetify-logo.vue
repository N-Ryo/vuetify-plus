<template>
  <img
    class="VuetifyLogo"
    alt="Vuetify Logo"
    src="/vuetify-logo.svg"
  >
</template>

<style>
.VuetifyLogo {
  height:calc(50px + 10vw);
  width: calc(50px + 10vw);
  transform: rotateY(560deg);
  animation: turn 3.5s ease-out forwards 1s;
}

@keyframes turn {
  100% {
    transform: rotateY(0deg);
  }
}
</style>
