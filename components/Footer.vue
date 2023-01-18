<template>
    <div class="w-full items-center  p-16 mt-4 md:mt-12 flex flex-col bg-[#ffffff] text-black font-space font-regular">
     <div class="max-w-screen-lg w-4/5">
        <div id="Logo" class="mb-12">
         <IconsLogo/>
      </div>
      <div id="menu" class="grid grid-cols-2 gap-4 md:grid-cols-4">
         <div class="flex flex-col">
            <div class="font-bold mb-2">Companie</div>
            <div>Despre noi</div>
            <div>Blog</div>
            <div>Investitori</div>
            <div>Impact</div>
         </div>
         <div class="flex flex-col">
            <div class="font-bold mb-2">Suport</div>
            <div>Tarife</div>
            <div>Cariere</div>
            <div>Comanda</div>
            <div>Devino partener</div>
         </div>
         <div class="flex flex-col">
            <div class="font-bold mb-2">General</div>
            <div>Termeni si conditii</div>
            <div>GDPR-Protectia Datelor</div>
         </div>
         <div class="flex flex-col">
            <div class="font-bold mb-2">Contact</div>
            <div>Ajutor</div>
         </div>
      </div>
      <div class="w-full h-[3px] my-6 rounded-full bg-[#565656]"></div>
      <div class="flex flex-col gap-2 md:flex-row md:justify-between mx-1 md:items-center">
        <div class="text-xs text-[#3e3e3e]">
            © 2023 Reciclon Inc. Toate drepturile rezervate.
        </div>
        <div class="flex flex-row gap-4 items-center">
            <IconsTwitter/>
            <IconsInstagram/>
            <IconsLinkedin/>
        </div>
      </div>
     </div>
    </div>
</template>

<script setup lang="ts">

</script>

