<script setup lang="ts">
useHead({
  meta: [{ name: 'viewport', content: 'width=device-width, initial-scale=1' }],
  link: [{ rel: 'icon', href: '/favicon.ico' }],
  htmlAttrs: {
    lang: 'pl',
  },
});

useSeoMeta({
  ogImage: 'https://i.ibb.co/7z2wHbF/grafika4.jpg',
  twitterImage: 'https://i.ibb.co/7z2wHbF/grafika4.jpg',
  twitterCard: 'summary_large_image',
  ogUrl: 'https://i.ibb.co/7z2wHbF/grafika4.jpg',
  twitterTitle: 'Salon Fryzur - Wojciech Gudzik.',
  twitterDescription: 'Odkryj swoją nową fryzurę już dziś',
});
</script>

<template>
  <Header />

  <UMain>
    <NuxtPage />
  </UMain>

  <Footer />
  <UNotifications />
</template>
