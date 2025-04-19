<script setup>

</script>

<template>
  <div ref="dark" class="">
  <div class="dark:text-teal-100 bg-gradient-to-br dark:from-emerald-950 dark:to-indigo-950 text-3xl/12 md:text-6xl h-full flex flex-col p-10">
    <div class="text-center">Pozdrav, ja sam <span class="dark:text-cyan-400 text-cyan-800">Davor Škiljić</span></div>
    <div class="border-b-2 my-8 rounded-full w-7/10 opacity-75 mx-auto"></div>
    <div class="dark:text-teal-100/75 m-auto md:m-0 text-xl md:text-2xl md:ps-10">Moji omiljeni filmovi:</div>
    <div class="flex flex-col md:flex-row items-center justify-around gap-10 mb-20">
      <div>
      <img class="w-full h-120 my-8 rounded-md" src="https://m.media-amazon.com/images/M/MV5BNzU2ODUxODgtNTdkYi00OTFmLWExNTctYWQ1NGVmYmQxNjMxXkEyXkFqcGc@._V1_.jpg">
      <p class="text-2xl text-center">The Lord of the Rings</p>
    </div>
    <div>
      <img class="w-full h-120 my-8 rounded-md object-cover" src="https://musicart.xboxlive.com/7/e0ee5100-0000-0000-0000-000000000002/504/image.jpg">
      <p class="text-2xl text-center">The Shawshank Redemption</p>
    </div>
    <div>
      <img class="w-full h-120 my-8 rounded-md" src="https://cdn.mojekarte.hr/m/2/210/images/8210-gladiator-poster-401x600.jpg ">
      <p class="text-2xl text-center">Gladiator</p>
    </div>
    </div>  
    <div @click="$refs.dark.classList.toggle('dark');" class="mb-6 text-2xl w-fit bg-cyan-700 text-white py-2 px-4 rounded self-center hover:bg-cyan-800">
  Toggle Dark Mode
</div>  
  </div>
</div>
</template>

<style scoped>

</style>
