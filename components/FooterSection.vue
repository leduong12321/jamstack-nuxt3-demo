<template>
  <footer class="py-12 text-white bg-brand-grey-800">
    <Container class="grid grid-cols-12 gap-6">
      <div class="col-span-12 md:col-span-6">
        <!-- <img :src="LogoWhite" class="w-32" alt="Pick a Sick Wick" /> -->
        <div>SHOP</div>
        <p
          class="py-4 md:w-4/5"
        >Le Thanh Duong @ 2022</p>
      </div>
      <div class="col-span-12 md:col-span-3">
        <Heading tag="h4" font-style="h4" color="text-white">Menu</Heading>
        <ul>
          <li class="underline list-disc list-inside">
            <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li class="underline list-disc list-inside">
            <nuxt-link to="/">About</nuxt-link>
          </li>
          <li class="underline list-disc list-inside">
            <nuxt-link to="/">Shop</nuxt-link>
          </li>
          <li class="underline list-disc list-inside">
            <nuxt-link to="/">Contact</nuxt-link>
          </li>
        </ul>
      </div>
      <div class="col-span-12 md:col-span-3">
        <Heading tag="h4" font-style="h4" color="text-white">Contact</Heading>
        <p>Binh Son, Quang Ngai</p>
      </div>
    </Container>
  </footer>
</template>

<script setup>
// We have to import images like this because Nuxt build doesn't incude them otherwsie
import LogoWhite from 'assets/images/logo-white.svg';
</script>