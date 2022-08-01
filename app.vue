<template>
<div>
  <Title>Pick a Sick Wick - Candle Shop</Title>
  <NuxtLayout :name="layout">
    <NuxtPage />
  </NuxtLayout>
</div>
  
</template>

<style>
body {
  @apply text-brand-grey bg-brand-beige-300;
}

.snipcart-modal__container {
  z-index: 100;
}
</style>

<script setup>
const router = useRouter();
const layout = "default";

// Scroll to top after each navigation
router.afterEach(() => {
  window.scrollTo(0, 0);
});
</script>