<template>
        <div class=" relative bg-gradient-to-br from-white to-[#f4f4f4] 
        rounded-[30px] px-12  py-8 flex flex-col border-2 border-gray-100
        shadow-md " :class="{'bg-gradient-to-br from-white to-blue-50 via-purple-50' :isHighlighted}">
        <div class=" text-3xl font-semibold text-center mb-4">
            {{ title }}
        </div>
        <div class="flex flex-row gap-0.5 content-center ">
            <div class="font-semibold  text-2xl content-center">
            {{ bags }} 
            </div>
            <IconsBag class="mt-0.5"/>

        </div>
        <div class="text-gray-400 prose-ul  mb-2 ">
            
           <div class="prose-li">3 Saci Metal</div>
           <div class="prose-li">3 Saci Hartie</div>
           <div class="prose-li">3 Saci Plastic</div>
           <div class="prose-li">3 Saci Sticla</div>
           <div class="prose-li text-black">5 Saci Universali</div>


        </div>
        <div class="text-3xl font-bold text-left font-space">
           {{ price }} RON
        </div>
        <div class="mt-4">
            <button class="rounded-lg font-space bg-black text-white px-8 py-3 flex flex-row gap-0.5 ">
                 <p>Continua</p>
                 <component :is="icons.arrow" class="h-5 mt-0.5 ml-0.5"></component>
            </button>
        </div>
        </div>
      
    
</template>

<script setup lang="ts">
import { HomeIcon, FilmIcon, PlusIcon, TrashIcon, ArrowLongRightIcon } from "@heroicons/vue/24/outline"

defineProps({
    title: String ,
    price: Number, 
    bags: Number,
    isHighlighted:Boolean,
})

const icons = reactive({
  home: HomeIcon,
  film: FilmIcon,
  plus: PlusIcon,
  trash: TrashIcon,
  arrow: ArrowLongRightIcon,
})
</script>

<style scoped>

</style>