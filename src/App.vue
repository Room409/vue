<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { ref } from 'vue'
const isScrolled = ref(false);

const handleScroll = () => {
  isScrolled.value = window.scrollY > 540;
};

window.addEventListener('scroll', handleScroll);
</script>

<template>
  <header class="w-full">
    <nav :class="{
      'bg-gray-50': isScrolled && $route.path === '/',
      'bg-transparent': !isScrolled && $route.path === '/',
      'transition-bg': isScrolled && $route.path === '/',
      'transition-down': !isScrolled && $route.path === '/',
      'bg-white': $route.path === '/peliculas'
    }"
      class="flex justify-evenly w-full mx-auto shadow-md py-3 fixed z-40  border-gray-300 border-b-2">
      <div class="flex items-center w-40">
        <RouterLink to="/"><img src="./assets/Logo-Cineplanet-1000x1000px-copia.png" alt=""> </RouterLink>
      </div>
      <ul :class="{ 'text-black': isScrolled }, { 'text-black': $route.path === '/peliculas' }"
        class="sm:flex color-custom gap-10 text-lg items-center text-white hidden ">
        <li>
          <RouterLink to="/peliculas" exact-active-class="link-active">Peliculas</RouterLink>
        </li>
        <li>
          <RouterLink to="">Promociones</RouterLink>
        </li>
        <li>
          <RouterLink to="">Socio</RouterLink>
        </li>
        <li>
          <RouterLink to="">Dulceria</RouterLink>
        </li>
        <li>
          <RouterLink to="">Blog</RouterLink>
        </li>
      </ul>
      <div class="flex justify-center items-center text-2xl gap-3 text-white"
        :class="{ 'text-black': isScrolled }, { 'text-black': $route.path === '/peliculas' }">
        <font-awesome-icon :icon="['fas', 'user']" />
        <font-awesome-icon :icon="['fasr', 'magnifying-glass']" />
      </div>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped>
.transition-bg {
  transition: 0.7s;
}

.transition-down {
  transition: 0.7s;
}
</style>
