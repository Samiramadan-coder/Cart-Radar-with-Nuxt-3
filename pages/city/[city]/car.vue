<template>
  <div>
    <div class="mt-32 flex">
      <CarSideBar />
      <NuxtPage />
    </div>
  </div>
</template>

<script setup>
const route = useRoute();

useHead({
  title: `Cars In ${route.params.city}`,
});
</script>
