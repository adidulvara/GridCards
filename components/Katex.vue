<template>
    <div class="" v-html="katexOutput">

    </div>
</template>

<script setup lang="ts">
import katex from 'katex'
const props = defineProps({
    element: {
        type: String,
        required: true,
    }
})
const text = ` \\begin{bmatrix} a & b \\\\ 
    c & d \\end{bmatrix}`;
const katexOutput = computed(() => {
    return katex.renderToString(props.element, {
        throwOnError: false,
        displayMode: true,
    })
})
</script>

<style scoped>

</style>