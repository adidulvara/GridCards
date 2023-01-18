<template>
    <div class="font-dm flex flex-col mx-10 md:mx-24 lg:mx-auto max-w-screen-xl h-screen">
         <div>
            Home
         </div>
       <div class="flex gap-2 items-center font-space font-medium text-lg">
        <Katex :element="'1/4'"/> times

       </div>        
    </div>
</template>

<script setup lang="ts">
const determinant = ' \\left|\\begin{array}{ccc} 1& 2&3  \\\\2  &  x+1 & 2x+1 \\\\  3&2x+1   &3x+1 \\end{array}\\right|=-1';
const fraction = ' \\Big(\\frac{5}{4}\\Big)^2 '
const integral= '\\int_{1}^{3} \\frac{\\sqrt{3x-6}}{x^2-1} \\cdot log_{2}{(32x)} dx'
</script>
<style scoped>

</style>