<template>
   <div class="flex flex-col h-screen max-w-screen-xl mx-10 font-dm md:mx-24 lg:mx-auto">
      <div class="mx-auto my-4 text-5xl font-bold text-center font-space">
         HomePage
      </div>
      <div class="flex items-center gap-2 text-lg font-medium font-space">
         <Katex :element="integral" /> times
         <Icon name="👨🏼‍🚀" class="text-red-400 " />
      </div>
   </div>
</template>

<script setup lang="ts">
const determinant = ' \\left|\\begin{array}{ccc} 1& 2&3  \\\\2  &  x+1 & 2x+1 \\\\  3&2x+1   &3x+1 \\end{array}\\right|=-1';
const fraction = ' \\Big(\\frac{5}{4}\\Big)^2 '
const integral = '\\int_{1}^{3} \\frac{\\sqrt{3x-6}}{x^2-1} \\cdot log_{2}{(32x)} dx'
const test = '\\sqrt{a^2 + b^2}'
</script>
<style scoped>

</style>