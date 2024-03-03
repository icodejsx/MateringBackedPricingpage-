<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
    <!-- <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav class="flex justify-between  items-center lg:py-10 py-10 px-4 lg:px-8 bg-[#e2e0e0]">
        <!-- <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink> -->

        <div>
          <img alt="Vue logo" class="logo" src="@/assets/mastering.png" width="250" height="" />
        </div>

        <a href="" class="text-2xl  font-bold">Log in</a>
      </nav>
    </div>
  </header>

  <RouterView />
</template>
