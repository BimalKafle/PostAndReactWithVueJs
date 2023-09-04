
<template>
  <main class="bg-[#43005A] ">
    <header>
      <div class=" flex bg-[#09001B]  p-4 shadow-md">
        <Navbar/>
      </div>
      <div class="flex">
        <div class=" w-1/6 h-max-fit bg-black opacity-75 ">
         <Sidebar/>
        </div>
        <div class="w-5/6  h-screen overflow-auto m-4 no-scrollbar">
          <MainContainer/>
         
        </div>
      </div>

    </header>
  </main>
</template>

<script>
import MainContainer from './components/MainContainer.vue'
import Navbar from './components/Navbar.vue'
import Sidebar from './components/Sidebar.vue'
export default {
  components:{
      MainContainer,
      Navbar,
      Sidebar
    }
}
</script>

<style>

</style>