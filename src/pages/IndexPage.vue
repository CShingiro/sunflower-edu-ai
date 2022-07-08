<script setup lang="ts"></script>

<template>
  <q-page class="row items-center justify-evenly q-pa-md q-gutter-md">
    <div class="col">
      <h3 class="text-center cairo text-italic">
        A Sunflower for the CountrySide
      </h3>
    </div>
    <div class="col">
      <transition>
        <q-img fit="fill" src="/images/SunflowerEduAI.svg"></q-img>
      </transition>
    </div>
    <div class="col">
      <q-btn
        to="/about"
        no-caps
        size="2rem"
        class="text-italic cairo bg-brown-4"
        >About</q-btn
      >
    </div>
    <div class="col">
      <q-btn
        to="/contact"
        no-caps
        size="2rem"
        class="text-italic cairo bg-brown-4"
        >Contact</q-btn
      >
    </div>
  </q-page>
</template>
