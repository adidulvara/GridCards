<template>
    <div class="flex mx-auto p-4 items-center w-full  max-w-screen-xl justify-between"> 
        <NuxtLink to="/">
       <IconsLogo/>
        </NuxtLink>
        <div class=" hidden sm:flex flex-row gap-4 font-space font-regular text-lg items-center justify-between ">
        <NuxtLink class="font-semibold"  to="/blog">Blog</NuxtLink>
        <NuxtLink  class="font-semibold" to="/pricing">Pricing</NuxtLink>
        <NuxtLink class=" text-white bg-black rounded-[7px] px-4 py-1" to="/pricing">Log in</NuxtLink>
       </div>
       <button class="flex sm:hidden">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-8 h-8">
  <path fillRule="evenodd" d="M3 6.75A.75.75 0 013.75 6h16.5a.75.75 0 010 1.5H3.75A.75.75 0 013 6.75zM3 12a.75.75 0 01.75-.75h16.5a.75.75 0 010 1.5H3.75A.75.75 0 013 12zm0 5.25a.75.75 0 01.75-.75h16.5a.75.75 0 010 1.5H3.75a.75.75 0 01-.75-.75z" clipRule="evenodd" />
</svg>

</button>
    </div>
</template>

<script setup lang="ts">
</script>

