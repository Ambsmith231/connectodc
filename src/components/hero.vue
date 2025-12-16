<template>
  <div class="grid w-100 h-autoo">
    <div class="font-bold text-3xl text-white">
      <h1 class="mt-8 mb-6 p-5 text-blue-200">Welcome to GeoGib Chatbot</h1>
    </div>
    <div
      class="text-2xl rounded w-130 p-4 text-white bg-linear-to-r from-orange-500"
    >
      <p class="text-blue-200">
        <span class="text-black font-weight-200 text-4xl">O</span>range
        <span class="text-black font-bold text-4xl">D</span>igital
        <span class="text-black font-bold text-4xl">C</span>enter
        <span
          class="bg-black p-1 md:font-bold rounded-full font-bold text-orange-400"
          >(ODC)</span
        >
        <br />
        <br />
        A place where visions are enligtened <br />
        <span>Misions are structured</span> <br />
        <span>Goals are become reality</span>
      </p>
    </div>
    <div class="flex justify-between items-center p-5">
      <a href="#">
        <button
          class="border border-blue-200 px-4 py-2 rounded text-blue-200 cursor-pointer hover:bg-blue-950/90 hover:text-blue-200 hover:scale-105 duration-300 ease-out"
        >
          Let's Chat
        </button>
      </a>
    </div>
    <Chatbox>
      <iframe
        src="https://cdn.botpress.cloud/webchat/v3.5/shareable.html?configUrl=https://files.bpcontent.cloud/2025/12/11/15/20251211153121-932FCRJ8.json"
        class="w-full h-full border-none"
        allow="microphone; camera"
      ></iframe>
    </Chatbox>
  </div>
</template>

<script setup>
import Chatbox from "./Chatbox.vue";
</script>

<style lang="scss" scoped></style>
