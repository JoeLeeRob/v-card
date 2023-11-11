<template>
  <div class="bg-slate-900 h-screen w-screen flex justify-center items-center">
    <div class="max-w-sm w-full bg-gray-600 relative">

        <div>
          <div class="w-full h-[200px]">
          <NuxtImg src="https://source.unsplash.com/random?landscape" class="w-full h-full object-cover"/>
        </div>

        <div class="flex flex-col items-center gap-8 relative bg-transparent top-[-75px]">
          <NuxtImg src="https://source.unsplash.com/random?profile"  class="w-[150px] h-[150px] rounded-full object-cover mx-auto"/>
          <div class="text-center text-gray-100">
            <p class="text-4xl font-semibold mb-2">Joseph Robinson</p>
            <p class="text-2xl">Software Developer</p>
          </div>
          <div class="my-8 w-full px-8">
            <button class="bg-blue-500 w-full hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
              Save My Contacts
            </button>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>
