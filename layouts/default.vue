<template>
  <div class="relative font-body">
    <HeaderSection />
    <div class="pt-24 bg-brand-beige-300">
      <slot />
      <div
        hidden
        id="snipcart"
        data-api-key="YjdhZjZjODgtMTMxYS00YWJkLTllM2ItYjAwZjYyMWY0ZTNiNjM3OTQ4NzIwNjQ1MDQ2OTU0"
      ></div>
    </div>
    <!-- <subscribe /> -->  
    <FooterSection />
  </div>
</template>



<style scoped>
body {
  -webkit-font-smoothing: antialiased;
}
</style>