<script setup lang="ts"></script>

<template>
  <q-page class="row items-center justify-evenly">
    <transition-group
      appear
      enter-active-class="animated fadeInLeft slower"
      leave-active-class="animated fadeInRight"
    >
      <div key="technology-div" class="col-12">
        <h2
          key="technology-title"
          class="gt-sm cairo text-bold text-center text-italic text-green-10"
        >
          About The Technology
        </h2>
        <h3
          key="technology-title"
          class="sm cairo text-bold text-center text-italic text-green-10"
        >
          About The Technology
        </h3>
        <h4
          key="technology-title"
          class="lt-sm cairo text-bold text-center text-italic text-green-10"
        >
          About The Technology
        </h4>
      </div>
      <div key="image-space" class="col-4 gt-sm"></div>
      <div key="image-space" class="col-3 sm"></div>
      <div key="image-div" class="col-4 gt-sm">
        <q-card key="image-card">
          <q-img key="image" src="/images/ITSModel.png"></q-img>
          <q-card-section key="image-section">
            <div
              key="image-title"
              class="text-h4 text-bold text-center text-green-7"
            >
              The Intelligent Tutoring System
            </div>
            <div key="image-content" class="text-h4">
              The intelligent tutoring system will work off of a knowledge base
              and learn and adjust according to user interaction with the
              interface. In this case, the user input will be primarily the
              student, but also the teacher, while the user interface will be
              the Sunflower.
            </div>
          </q-card-section>
        </q-card>
      </div>
      <div key="image-div" class="col-6 sm">
        <q-card key="image-card">
          <q-img key="image" src="/images/ITSModel.png"></q-img>
          <q-card-section key="image-section">
            <div
              key="image-title"
              class="text-h5 text-bold text-center text-green-7"
            >
              The Intelligent Tutoring System
            </div>
            <div key="image-content" class="text-h5">
              The intelligent tutoring system will work off of a knowledge base
              and learn and adjust according to user interaction with the
              interface. In this case, the user input will be primarily the
              student, but also the teacher, while the user interface will be
              the Sunflower.
            </div>
          </q-card-section>
        </q-card>
      </div>
      <div key="image-div" class="col-12 lt-sm">
        <q-card key="image-card">
          <q-img key="image" src="/images/ITSModel.png"></q-img>
          <q-card-section key="image-section">
            <div
              key="image-title"
              class="text-h6 text-bold text-center text-green-7"
            >
              The Intelligent Tutoring System
            </div>
            <div key="image-content" class="text-h6">
              The intelligent tutoring system will work off of a knowledge base
              and learn and adjust according to user interaction with the
              interface. In this case, the user input will be primarily the
              student, but also the teacher, while the user interface will be
              the Sunflower.
            </div>
          </q-card-section>
        </q-card>
      </div>
      <div key="image-space-2" class="col-4 gt-sm"></div>
      <div key="image-space-2" class="col-3 sm"></div>
    </transition-group>
    <transition-group
      appear
      enter-active-class="animated fadeInRight slower"
      leave-active-class="animated fadeInRight"
    >
      <div key="application-div" class="col-12">
        <h2
          key="application-title"
          class="gt-sm cairo text-bold text-center text-italic text-green-10"
        >
          About The Application
        </h2>
        <h3
          key="application-title"
          class="sm cairo text-bold text-center text-italic text-green-10"
        >
          About The Application
        </h3>
        <h4
          key="application-title"
          class="lt-sm cairo text-bold text-center text-italic text-green-10"
        >
          About The Application
        </h4>
      </div>
      <div key="pwa-space" class="col-4 gt-sm"></div>
      <div key="pwa-space" class="col-3 sm"></div>
      <div key="pwa-div" class="col-4 gt-sm">
        <q-img key="pwa-img" src="/images/PWALogo.png"></q-img>
      </div>
      <div key="pwa-div" class="col-6 sm">
        <q-img key="pwa-img" src="/images/PWALogo.png"></q-img>
      </div>
      <div key="pwa-div" class="col-12 lt-sm">
        <q-img key="pwa-img" src="/images/PWALogo.png"></q-img>
      </div>
      <div key="pwa-space-2" class="col-4 gt-sm"></div>
      <div key="pwa-space-2" class="col-3 sm"></div>
      <div key="pwa-info-space" class="col-4 gt-sm"></div>
      <div key="pwa-info-space" class="col-3 sm"></div>
      <div key="pwa-info" class="col-4 gt-sm">
        <h4>
          The app will be a progressive app that runs on web related
          technologies such as HTML CSS and JavaScript. We will use the Vue
          front end framework and code the algorithm with JavaScript. When the
          knowledge base is installed and it is downloaded with a database, the
          app will still be usable offline.
        </h4>
      </div>
      <div key="pwa-info" class="col-6 sm">
        <h5>
          The app will be a progressive app that runs on web related
          technologies such as HTML CSS and JavaScript. We will use the Vue
          front end framework and code the algorithm with JavaScript. When the
          knowledge base is installed and it is downloaded with a database, the
          app will still be usable offline.
        </h5>
      </div>
      <div key="pwa-info" class="col-12 lt-sm">
        <h6>
          The app will be a progressive app that runs on web related
          technologies such as HTML CSS and JavaScript. We will use the Vue
          front end framework and code the algorithm with JavaScript. When the
          knowledge base is installed and it is downloaded with a database, the
          app will still be usable offline.
        </h6>
      </div>
      <div key="pwa-info-space-2" class="col-4 gt-sm"></div>
      <div key="pwa-info-space-2" class="col-3 sm"></div>
    </transition-group>
  </q-page>
</template>

<style scoped></style>
