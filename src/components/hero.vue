<template>
  <div class="flex flex-col max-w-full bg-blue-950 w-auto mx-auto md:w-10xl">
    <div class="pt-30 p-6 flex flex-col items-center justify-center gap-2 sm:space-y-6 md:space-y-10 lg:space-y-14 bg-gray-800">  
      <div class="font-bold mx-auto h-fit w-fit text-white rounded shadow-xl/30 shadw-blue-800/50 bg-blue-950">
        <h1 class="p-5 text-center text-3xl text-blue-200">Welcome to <span class="text-orange-500 text-4xl">GeoGib</span>  Chatbot</h1>
        <p class="p-2 text-center text-2xl text-blue-200">An integrated chatbot where all your messenger chats are managed</p>
      </div>
      <div class="p-4 italic text-blue-200 w-fit h-fit mx-auto">
        <p> <span class="bg-linear-to-r from-orange-900 p-2">No Scaping,</span> <span class="p-2 bg-linear-to-r from-orange-900">Keep Chating;</span> <span class="p-2 bg-linear-to-r from-orange-900">Just a Pop-up!</span></p>
      </div>
    </div> <hr class="my-30 border-2 border-gray-900">

    <div class=" flex flex-col mx-auto items-center justify-center min-h-screen">
      <div class="mx-auto p-2 w-3/4 h-fit pt-2 gap-2 flex flex-col items-center justify-center rounded">
        <div class="flex flex-col mx-auto shadow-xl/30 shadw-blue-800/50 border-blue-900 border-y-4 text-center w-2/3 text-2xl rounded p-6 text-white bg-blue-950">
          
            <p class="text-blue-200">P<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="2 -4 20 35" stroke-width="1.5" stroke="currentColor" class="size-14 inline w-fit  text-red-500"><path stroke-linecap="round" stroke-linejoin="round" d="m3.95 13.5 10.5-11.25L12 10.5h8.25L9.75 21.75 12 13.5H3.75Z" /></svg>wered by:
          <div class="flex flex-wrap items-center justify-center">   
                <span class="font-weight-200 text-3xl text-orange-500">Orange</span>
                <span class="font-bold text-3xl p-1">Digital</span>
                <span class="font-bold text-3xl">Center</span>
                <span class="p-2 md:font-bold text-3xl rounded-full font-bold text-orange-500">(ODC)</span>
          </div>   
              <br />
              <br />
              <div class="flex flex-col gap-2 items-center text-blue-200">
                <span class="shadow-3xl block w-fit  bg-linear-to-r from-orange-900 shadow-gray-800 border-blue-900 rounded p-2"> A place where visions are enligtened, </span>
                <span class="shadow-3xl w-fit bg-linear-to-r from-orange-900 shadow-orange-950 border-blue-900 rounded p-2">Misions are structured,</span>
                <span class="shadow-3xl w-fit bg-linear-to-r from-orange-900 shadow-gray-800 rounded border-blue-900 p-2">Goals become reality.</span>
              </div>
            </p>
          
        </div>
        <div class="items-center p-5">
          <a href="#">
            <button class="border border-blue-800 p-2 w-30 rounded text-blue-200 cursor-pointer hover:bg-blue-900/90 hover:text-blue-200 hover:scale-105 duration-300 ease-out">
              Let's Chat
            </button>
          </a>
        </div>
      </div>
    </div> 
    
    <div class="bg-gray-800 mx-auto flex items-center justify-center min-h-100 gap-10">
      <div class="p-10 mx-auto gap-8 md:w-full grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 max-w-7xl w-full">
        <div id="main-div-connect-1" class="bg-blue-950 border-blue-900 rounded flex flex-col pt-6 p-4 shadow-xl/30 shadw-blue-800/50"> 
          <div class=" flex flex-col gap-2">
            <div class="text-blue-200 text-2xl font-serif font-extrabold">
              <p>Your special <span class="text-orange-500 font-bold text-3xl">Date</span></p>
            </div> <hr>
            <div class="text-blue-200 text-lg">
              <p>Connecting with Purpose</p>
            </div>
            <div class="text-blue-200 text-lg">
              <p>Dating is a choice not compulsory.</p>
            </div>
          </div> 
        </div>

        <div id="main-div-connect-2" class="bg-blue-950 border-blue-900 rounded flex flex-col pt-6 p-4 shadow-xl/30 shadw-blue-800/50">
          <div class=" flex flex-col gap-2">
            <div class="text-blue-200 text-2xl font-serif font-extrabold">
              <p>Find Your <span class="text-orange-500 font-bold text-3xl"> Coach </span></p>
            </div> <hr>
            <div class="text-blue-200 text-lg">
              <span class=" w-fit  bg-linear-to-r from-orange-900 shadow-gray-800 border-blue-900">Emotions</span>  will get you acting; <br> <span class="w-fit bg-linear-to-r from-orange-800 shadow-gray-800 border-blue-900">IQ </span>will get you reasoning before actions are taken.
            </div>
          </div>
        </div>

        <div id="main-div-connect-3" class="bg-blue-950 border-blue-900 rounded flex flex-col pt-6 p-4 shadow-xl/30 shadw-blue-800/50"> 
          <div class=" flex flex-col gap-2">
            <div class="text-blue-200 text-2xl font-serif font-extrabold">
              <p>Current <span class="text-orange-500 font-bold text-3xl">My Speck</span> </p>
            </div> <hr>
            <div class="text-blue-200 text-lg">
              <span class="w-fit  bg-linear-to-r from-orange-900 shadow-gray-800 border-blue-900">"Not all that glitters, is gold."</span> <br> A glimpse of the eye could be real after further obsevations.
            </div>
          </div>
        </div>  
      </div>
    </div>

    <div>
      <Chatbox>
        <iframe
          src="https://cdn.botpress.cloud/webchat/v3.5/shareable.html?configUrl=https://files.bpcontent.cloud/2025/12/11/15/20251211153121-932FCRJ8.json"
          class="w-full h-full border-none"
          allow="microphone; camera"
        ></iframe>
      </Chatbox>
    </div>
  </div>
</template>

<script setup>
import Chatbox from "./Chatbox.vue";
</script>

<style lang="scss" scoped></style>
