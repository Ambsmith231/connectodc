<template>
  <div class=" mx-auto max-w-7xl">
    <nav
      class="bg-blue-950 border border-blue-900 flex flex-col md:flex-row mx-auto justify-between px-2 text-2xl text-bold text-white gap-2">
      <div class="py-2 ">
        <button
          class="uppercase text-sm text-blue-200 cursor-pointer hover:bg-blue-900/90 hover:text-blue-200 hover:scale-105 duration-300 ease-out px-2 py-1 md:px-2 md:py-1 rounded-2xl"
        >
          🏠 Home
        </button>
      </div>
      <div class="flex flex-col md:flex-row md:gap-5 sm:gap-1 justify-between gap-5 py-5 px-4 text-[11px]">
        <a href="login">
          <button
            class="uppercase border-2 border-blue-200 text-blue-200 cursor-pointer hover:bg-blue-900/90 hover:text-blue-200 hover:scale-105 duration-300 ease-out px-2 py-1 md:px-2 md:py-1 rounded-2xl"
          >
            login
          </button>
        </a>

        <a href="singup">
          <button
            class="uppercase border-2 border-blue-200 text-blue-200 cursor-pointer hover:bg-blue-900/90 hover:text-blue-200 hover:scale-105 duration-300 ease-out px-2 py-1 md:px-2 md:py-1 rounded-2xl"
          >
            Sigup
          </button>
        </a>

        <router-link to="/about">
          <a href="about">
            <button
              class="uppercase border-2 border-blue-200 text-blue-200 cursor-pointer hover:bg-blue-900/90 hover:text-blue-200 hover:scale-105 duration-300 ease-out px-2 py-1 md:px-2 md:py-1 rounded-2xl"
            >
              About Us
            </button>
          </a>
        </router-link>
      </div>
    </nav>
  </div>
</template>

<script setup>
import { useRoute, useRouter } from "vue-router";
</script>

<style lang="scss" scoped></style>
