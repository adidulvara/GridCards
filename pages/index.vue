<template>
    <div class="font-dm flex flex-col mx-10 md:mx-24 lg:mx-auto max-w-screen-xl h-screen">
         <div>
            Home
         </div>
         <Katex :element="equation"/>
        
    </div>
</template>

<script setup lang="ts">
const equation = ' \\left|\\begin{array}{ccc} 1& 2&3  \\\\2  &  x+1 & 2x+1 \\\\  3&2x+1   &3x+1 \\end{array}\\right|=-1'
</script>
<style scoped>

</style>