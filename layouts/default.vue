<template>
   <div>
    <div class="font-dm flex flex-col mx-10 md:mx-24 lg:mx-auto max-w-screen-lg h-screen">
    <Navbar v-if="!onLoginPage"/>
        <slot/>
    </div>
   </div>
</template>
<script setup lang="ts">
import { useRoute } from 'vue-router';
const route= useRoute();
const onLoginPage = computed(() => {
      return route.path === '/login'
    })
    

</script>