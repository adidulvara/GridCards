<template>
    <div class="px-2 py-4 my-16 text-5xl font-bold text-left font-space ">
        Pachete Reciclon
    </div>
    <div class="grid justify-around grid-cols-1 gap-4 sm:grid-cols-2 lg:grid-cols-3 lg:gap-x-12">
        <Card v-for="product in products" :bags="product.bags" :title="product.title" :price="product.price"
            :isHighlighted="product.isHighlighted" />
    </div>
</template>

<script setup lang="ts">

interface Product {
    title: string;
    price: number;
    bags: number;
    isHighlighted: boolean;
}

const products: Product[] = [
    { title: 'Starter', price: 400, bags: 20, isHighlighted: false, },
    { title: 'Coffee Shop', price: 600, bags: 40, isHighlighted: true, },
    { title: 'Restaurant', price: 800, bags: 80, isHighlighted: false, },
    { title: 'School', price: 1200, bags: 140, isHighlighted: false, },
    { title: 'Enterprise', price: 2000, bags: 200, isHighlighted: false, },
    { title: 'Custom', price: 8000, bags: 800, isHighlighted: false, },

]

</script>

<style scoped>

</style>