<template>
    <div>
        <div class="flex flex-col gap-[8px] bg-white shadow-xl rounded-[8px]
        px-24 py-16 items-center">
            <IconsLogo class="mb-8" />
            <div class="font-dm font-medium text-black">
                <div class="text-xl w-80 mb-2">
                    Introduceti nr. de telefon
                    sau adresa de email
                </div>
                <div>
                    <input class="rounded-[8px]  w-full px-8 py-3.5
                 bg-[#ebebeb] font-space placeholder-zinc-600 focus:outline-none " type="text" placeholder="+407...">
                </div>
                <button @click="" class="w-80 text-white mt-2 bg-black rounded-[8px] 
            text-center font-dm text-lg items-center justify-center flex flex-row gap-1
            font-normal px-4 py-3.5">
                    <div class="">
                        Continua
                    </div>
                    <component class="h-6 hidden" :is="icons.arrowRight"></component>

                </button>
                <div class="bg-[#D9D9D9] h-[2px] mx-1 mt-4 mb-2 rounded-full"></div>
            </div>
            <div class="flex flex-col gap-[8px]">
                <button>
                    <ButtonsSocialGoogle />
                </button>
                <button>
                    <ButtonsSocialApple />
                </button>
                <button>
                    <ButtonsSocialTwitter />
                </button>
            </div>
            <div class="text-[10px] text-left text-zinc-500 w-80">
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
                industry's standard dummy text ever since the 1500s.
            </div>
        </div>

    </div>
</template>

<script setup lang="ts">
import { HomeIcon, FilmIcon, PlusIcon, ArrowLongRightIcon } from "@heroicons/vue/24/solid"

const icons = reactive({
    home: HomeIcon,
    film: FilmIcon,
    plus: PlusIcon,
    arrowRight: ArrowLongRightIcon,
})
</script>

<style scoped>

</style>