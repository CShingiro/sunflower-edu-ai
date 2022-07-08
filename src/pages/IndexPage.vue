<script setup lang="ts"></script>

<template>
  <q-page class="row items-center justify-evenly q-pa-md q-gutter-md">
    <div class="col">
      <transition-group
        appear
        enter-active-class="animated fadeInLeft slower"
        leave-active-class="animated fadeOutLeft"
      >
        <h2
          key="project-title"
          class="text-center cairo text-italic text-bold text-green-10"
        >
          SunflowerEdu AI
        </h2>
        <h3
          key="slogan"
          class="text-center cairo text-italic text-bold text-green-7"
        >
          A Sunflower for the CountrySide
        </h3>
      </transition-group>
    </div>
    <div class="col">
      <transition
        appear
        enter-active-class="animated bounceInDown slower"
        leave-active-class="animated bounceOutUp"
      >
        <q-img
          class="draw-in"
          fit="fill"
          src="/images/SunflowerEduAI.svg"
        ></q-img>
      </transition>
    </div>
    <div class="col">
      <transition
        appear
        enter-active-class="animated bounceIn slower"
        leave-active-class="animated bounceOut"
      >
        <q-btn
          to="/about"
          no-caps
          size="2rem"
          class="text-italic cairo bg-brown-4"
          >About</q-btn
        >
      </transition>
    </div>
  </q-page>
</template>

<style scoped>
.draw-in {
  stroke-width: 10px;
  stroke: green;
}
</style>
