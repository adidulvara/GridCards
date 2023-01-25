<template>
    <div class=" relative bg-gradient-to-br text-[#1e1e1e] from-white to-[#f4f4f4] 
        rounded-[30px] px-12  py-8 flex flex-col border-2 border-gray-100
        shadow-md " :class="{ 'bg-gradient-to-br from-white to-blue-50 via-purple-50': isHighlighted }">
        <div class="mb-4 text-3xl font-semibold text-center ">
            {{ title }}
        </div>
        <div class="flex flex-row gap-0.5 content-center ">
            <div class="content-center text-2xl font-semibold">
                {{ bags }}
            </div>
            <IconsBag class="mt-0.5" />

        </div>
        <div class="mb-2 text-gray-400 prose-ul ">

            <div class="prose-li">3 Saci Metal</div>
            <div class="prose-li">3 Saci Hartie</div>
            <div class="prose-li">3 Saci Plastic</div>
            <div class="prose-li">3 Saci Sticla</div>
            <div class="text-black prose-li">5 Saci Universali</div>


        </div>
        <div class="text-3xl font-bold text-left font-space">
            {{ price }} RON
        </div>
        <div class="mt-4">
            <button class="rounded-lg font-space bg-black text-white px-8 py-3 flex flex-row gap-0.5 ">
                <p>Continua</p>
            </button>
        </div>
    </div>


</template>

<script setup lang="ts">



defineProps({
    title: String,
    price: Number,
    bags: Number,
    isHighlighted: Boolean,
})


</script>

<style scoped>

</style>