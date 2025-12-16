<template>
  <div>
    <button
      @click="toggleChat"
      :class="[
        'fixed bottom-5 right-5 w-16 h-16 rounded-full border-none cursor-pointer shadow-lg z-50 transition duration-300 ease-in-out',
        isOpen
          ? 'bg-red-500 hover:bg-red-600 transform hover:scale-105'
          : 'bg-blue-500 hover:bg-blue-600 transform hover:scale-105',
      ]"
      aria-label="Toggle Chatbot"
    >
      <span v-if="!isOpen" class="flex items-center justify-center">
        <img
          src="/src/image/chat.png"
          alt="chat icon"
          class="h-10 w-10 object-contain rounded-full"
        />
      </span>
      <span v-else class="text-white text-2xl">✖</span>
    </button>

    <transition name="slide-up">
      <div
        v-if="isOpen"
        class="fixed bottom-24 right-5 w-80 h-96 bg-white rounded-xl shadow-2xl flex flex-col overflow-hidden z-40"
      >
        <header
          class="p-3 bg-blue-500 text-white rounded-t-xl flex justify-between items-center"
        >
          <h3 class="text-lg font-semibold">Chat with Us!</h3>
        </header>

        <div class="flex-grow p-0 overflow-y-auto">
          <slot></slot>
        </div>
      </div>
    </transition>
  </div>
</template>

<script>
export default {
  name: "Chat-Dialog",
  data() {
    return {
      isOpen: false,
    };
  },
  methods: {
    toggleChat() {
      this.isOpen = !this.isOpen;
    },
  },
};
</script>
