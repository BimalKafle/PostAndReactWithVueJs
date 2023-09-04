<template>
      <div class="flex flex-row  w-full">
        <div class="basis-1/4 ">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mt-1 text-white">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
            <span class="text-[#2BE9F0] ml-2 text-2xl font-extrabold   font-serif">Post and Reaction</span>
            </svg>
        </div>
        <div class="basis-1/2 "  >
            <Searchbar/>
        </div>
        <div class="basis-1/4 ">
            <NabbarLogin/>
        </div>

        
      </div>
</template>

<script>
import NabbarLogin from './NabbarLogin.vue'
import Searchbar from './Searchbar.vue'

export default {
    components:{
        Searchbar,
        NabbarLogin
    }
}
</script>

<style>

</style>