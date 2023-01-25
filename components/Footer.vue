<template>
   <div class="flex flex-col items-center w-full p-16 mt-4 md:mt-12 font-space font-regular">
      <div class="w-4/5 max-w-screen-lg">
         <div id="Logo" class="mb-12">
            <IconsLogo />
         </div>
         <div id="menu" class="grid grid-cols-2 gap-4 md:grid-cols-4">
            <div class="flex flex-col">
               <div class="mb-2 font-bold">Companie</div>
               <div>Despre noi</div>
               <div>Blog</div>
               <div>Investitori</div>
               <div>Impact</div>
            </div>
            <div class="flex flex-col">
               <div class="mb-2 font-bold">Suport</div>
               <div>Tarife</div>
               <div>Cariere</div>
               <div>Comanda</div>
               <div>Devino partener</div>
            </div>
            <div class="flex flex-col">
               <div class="mb-2 font-bold">General</div>
               <div>Termeni si conditii</div>
               <div>GDPR-Protectia Datelor</div>
            </div>
            <div class="flex flex-col">
               <div class="mb-2 font-bold">Contact</div>
               <div>Ajutor</div>
            </div>
         </div>
         <div class="w-full h-[3px] my-6 rounded-full bg-[#f8f8f8]"></div>
         <div class="flex flex-col gap-2 mx-1 md:flex-row md:justify-between md:items-center">
            <div class="text-xs text-[#f8f8f8]">
               © 2023 Reciclon Inc. Toate drepturile rezervate.
            </div>
            <div class="flex flex-row gap-4 items-center text-[#f8f8f8]">
               <IconsTwitter />
               <IconsInstagram />
               <IconsLinkedin />
            </div>
         </div>
      </div>
   </div>
</template>

<script setup lang="ts">

</script>

