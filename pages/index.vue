<template>
    <div class="font-dm flex flex-col mx-10 md:mx-24 lg:mx-auto max-w-screen-xl h-screen">
        <Navbar/>
        <div class="text-5xl text-left font-space font-bold py-4 px-2 my-16 ">
           Pachete Reciclon
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 justify-around gap-4  lg:gap-x-12">
            <Card  v-for="product in products" :bags="product.bags" :title="product.title"
        :price="product.price" :isHighlighted="product.isHighlighted"/>
        </div>
    </div>
</template>

<script setup lang="ts">

interface Product { 
    title: string;
    price: number; 
    bags: number;
    isHighlighted: boolean;
}

const products: Product[]=[
    {title:'Starter', price:400, bags:20,isHighlighted:false,},
    {title:'Coffee Shop', price: 600, bags:40,isHighlighted:true,},
    {title:'Restaurant', price:800, bags: 80,isHighlighted:false,},
    {title:'School', price:1200, bags: 140,isHighlighted:false,},
    {title:'Enterprise', price:2000, bags: 200,isHighlighted:false,},
    {title:'Custom', price:8000, bags: 800,isHighlighted:false,},

]

</script>

<style scoped>

</style>