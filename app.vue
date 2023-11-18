<template>
  <div class="bg-slate-900 min-h-screen p-8 w-screen flex justify-center ">
    <div class="max-w-sm w-full h-fit bg-slate-950 relative">

        <div>
          <div class="w-full h-[200px]">
          <NuxtImg src="https://source.unsplash.com/random?technology" class="w-full h-full object-cover"/>
        </div>

        <div class="flex flex-col items-center p-2 gap-8 relative top-[-75px]">
          <NuxtImg :src="profilePicture"  class="w-[150px] h-[150px] rounded-full object-cover object-[37%] mx-auto"/>
          <div class="text-center text-gray-100">
            <p class="text-4xl font-semibold mb-2">Joseph Robinson</p>
            <p class="text-2xl font-light">Software Developer</p>
          </div>
          <div class="my-8 w-full px-8">
            <a class="bg-slate-700 w-full hover:bg-slate-800 text-white font-bold py-2 px-4 rounded block text-center"
              :href="contactCard"
              download
              target="_blank"
            >
              Save My Contact
            </a>
          </div>
          <div class="text-white flex gap-4">
            <a href="http://www.linkedin.com/in/joeleerob"
               class="border-gray-100 rounded-full border-2 p-2 w-[55px] h-[55px] flex items-center justify-center"
               target="_blank"
            >
              <Icon name="ri:linkedin-fill" size="2rem" />
            </a>
            <a href="https://github.com/JoeLeeRob"
               class="border-gray-100 rounded-full border-2 p-2 w-[55px] h-[55px] flex items-center justify-center"
               target="_blank"
            >
              <Icon name="uil:github" size="2rem" />
            </a>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script setup>
const contactCard = ref('/contact.vcf')
const profilePicture = ref('/Joe_Profile_400.jpg')
</script>
