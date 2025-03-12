<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="wrapper">
    <div class="text-3xl">yep</div>
    <nav>
      <RouterLink
        activeClass="opacity-60"
        class="underline text-living-coral hover:opacity-60"
        to="/"
      >
        Home
      </RouterLink>

      <RouterLink
        activeClass="opacity-60"
        class="underline text-living-coral hover:opacity-60"
        to="/about"
      >
        About
      </RouterLink>
    </nav>
  </div>

  <RouterView />
</template>
