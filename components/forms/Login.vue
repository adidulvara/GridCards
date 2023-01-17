<template>
    <div>
        <div class="flex flex-col gap-[8px] bg-white shadow-xl rounded-[8px]
        px-16 py-12 items-center">
        <IconsLogo class="mb-8"/>
        <div class="font-dm font-medium text-black">
            <div class="text-xl w-80 mb-2">
                Introduceti nr. de telefon 
            sau adresa de email
            </div>
            <div>
                <input class="rounded-[8px]  w-full px-8 py-3.5
                 bg-[#ebebeb] font-space placeholder-zinc-600 focus:outline-none " type="text" placeholder="+407...">
            </div>
            <div class="text-white mt-2 bg-black rounded-[8px] 
            text-center font-dm text-lg  font-normal px-4 py-3.5">
                <button class="">
                Continua
            </button>
            </div>
            <div class="bg-[#D9D9D9] h-[2px] mx-1 mt-4 mb-2 rounded-full"></div>
        </div>
        <div class="flex flex-col gap-[8px]">
            <button>
         <ButtonsSocialGoogle/>
         </button>
         <button>
         <ButtonsSocialApple/>
         </button>
         <button>
         <ButtonsSocialTwitter/>
         </button>
        </div>
         </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>