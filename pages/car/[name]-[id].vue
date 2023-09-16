<template>
  <div>
    <CarDetailsHero />
    <CarDetailsAttribute />
    <CarDetailsDescription />
    <CarDetailsContact />
  </div>
</template>

<script setup>
const route = useRoute();

useHead({
  title: route.params.name
});

// definePageMeta({
//   layout: 'custom'
// });
</script>
