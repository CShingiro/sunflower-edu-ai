<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated class="bg-brown-4">
      <q-toolbar>
        <q-btn flat dense round aria-label="Menu" @click="toggleLeftDrawer">
          <q-icon size="60px" name="img:/images/SunflowerEduAI.svg"></q-icon>
        </q-btn>

        <q-toolbar-title class="cairo text-bold text-italic gt-xs">
          SunfowerEdu AI
        </q-toolbar-title>
        <q-space class="gt-md" />
        <q-space class="gt-md" />
        <q-space class="gt-md" />
        <q-space class="gt-sm" />
        <q-space class="lt-sm" />
        <q-toolbar-title class="cairo text-bold text-italic gt-xs"
          >Brought to you by:</q-toolbar-title
        >
        <q-btn
          target="_blank"
          class="bg-orange-2"
          href="https://www.tsinghua.edu.cn/en/index.htm"
        >
          <q-icon name="img:/images/tsinghua-university.jpg"></q-icon>
        </q-btn>
        <q-btn
          target="_blank"
          class="bg-orange-2"
          href="https://sociallyradicalwebdesign.com"
        >
          <q-icon name="img:/images/SRWBLogo.png"></q-icon>
        </q-btn>
        <q-btn
          target="_blank"
          class="bg-orange-2"
          href="https://www.tsinghua.edu.cn/gss/"
        >
          <q-icon name="img:/images/logo1.png"></q-icon>
        </q-btn>
        <q-btn
          target="_blank"
          class="bg-orange-2"
          href="https://www.undp.org/sustainable-development-goals"
        >
          <q-icon name="img:/images/SDG-goals-logo.jpg"></q-icon>
        </q-btn>
      </q-toolbar>
    </q-header>

    <q-drawer v-model="leftDrawerOpen" show-if-above behavior="mobile" bordered>
      <q-list>
        <q-item-label header> Home Menu </q-item-label>

        <EssentialLink
          v-for="link in linksList"
          :key="link.title"
          v-bind="link"
        />
      </q-list>
    </q-drawer>

    <q-page-container class="bg-orange-2">
      <router-view />
    </q-page-container>
    <q-footer>
      <q-toolbar class="bg-brown-4">
        <q-btn flat dense round target="_blank" aria-label="Facebook">
          <q-icon name="facebook" color="orange-2"></q-icon>
        </q-btn>
        <q-btn flat dense round target="_blank" aria-label="Instagram">
          <q-icon name="ion-logo-instagram" color="orange-2"></q-icon>
        </q-btn>
        <q-btn flat dense round target="_blank" aria-label="Twitter">
          <q-icon name="ion-logo-twitter" color="orange-2"></q-icon>
        </q-btn>
        <q-btn flat dense round target="_blank" aria-label="Rumble">
          <q-icon name="ion-logo-youtube" color="orange-2"></q-icon>
        </q-btn>
        <q-space />
        <q-btn
          no-caps
          flat
          dense
          class="cairo"
          href="https://en.wikipedia.org/wiki/Fair_dealing_in_Canadian_copyright_law"
          target="_blank"
          aria-label="Fair Use Copyright 2021 Socially Radical Guitarist"
        >
          <q-icon name="copyright" color="orange-2"></q-icon>
          2022 - Fair Use - SunflowerEduAI
        </q-btn>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script setup lang="ts">
import { ref } from 'vue';
import EssentialLink from 'components/EssentialLink.vue';

const linksList = [
  {
    title: 'Home',
    caption: 'Sunflower Page',
    icon: 'ion-home',
    link: '/',
  },
  {
    title: 'About',
    caption: 'About the Project',
    icon: 'ion-information-circle-outline',
    link: '/about',
  },
  {
    title: 'Contact',
    caption: 'Contact Page',
    icon: 'ion-mail',
    link: '/contact',
  },
];

const leftDrawerOpen = ref(false);

const toggleLeftDrawer = () => {
  leftDrawerOpen.value = !leftDrawerOpen.value;
};
</script>
