<script setup lang="ts"></script>

<template>
  <q-page class="row items-center justify-evenly q-pa-md q-gutter-md">
    <div class="col gt-md">
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
          A Sunflower for the Countrysite
        </h3>
      </transition-group>
    </div>
    <div class="col-12 lt-lg">
      <transition-group
        appear
        enter-active-class="animated fadeInLeft slower"
        leave-active-class="animated fadeOutLeft"
      >
        <h2
          key="project-title"
          class="gt-xs text-center cairo text-italic text-bold text-green-10"
        >
          SunflowerEdu AI
        </h2>
        <h3
          key="project-title"
          class="lt-sm text-center cairo text-italic text-bold text-green-10"
        >
          SunflowerEdu AI
        </h3>
        <h3
          key="slogan"
          class="gt-xs text-center cairo text-italic text-bold text-green-7"
        >
          A Sunflower for the CountrySide
        </h3>
        <h5
          key="slogan"
          class="lt-sm text-center cairo text-italic text-bold text-green-7"
        >
          A Sunflower for the CountrySide
        </h5>
      </transition-group>
    </div>
    <div class="col gt-xs">
      <transition
        appear
        enter-active-class="animated bounceInDown slower"
        leave-active-class="animated bounceOutUp"
      >
        <q-img fit="fill" src="/images/SunflowerEduAI.svg"></q-img>
      </transition>
    </div>
    <div class="col-12 lt-sm">
      <transition
        appear
        enter-active-class="animated fadeInRight slower"
        leave-active-class="animated fadeOutRight"
      >
        <q-img fit="fill" src="/images/SunflowerEduAI.svg"></q-img>
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
    <div class="col">
      <transition
        appear
        enter-active-class="animated bounceIn slower"
        leave-active-class="animated bounceOut"
      >
        <q-btn
          to="/contact"
          no-caps
          size="2rem"
          class="text-italic cairo bg-brown-4"
          >Contact</q-btn
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
