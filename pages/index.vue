<template>
  <div class="h-screen bg-dirty-gray relative">
    <div class='m-5 absolute'>
      <nav>
         <img src="~/assets/logo.png" class="h-20 m-5">
      </nav>
       <div class="m-7 text-base">
         <NuxtLink to="/about">
           About
         </NuxtLink>
       </div>
       <div class="m-7 text-base">
         <NuxtLink to="/projects">
           Github Repositories
         </NuxtLink>
       </div>
       <div class="m-8 h-96 flex flex-wrap content-center">
          <div>
          <h1 class="text-6xl mt-8">Mark Joseph Colibao</h1>
          <h3 class="text-4xl mt-3">Web Developer</h3>
          <p class="text-2xl font-sans font-thin mt-4">Codes codes lang! Check out my repository.</p>
          </div>
       </div>
    </div>
    <Background/>
  </div>
</template>

<script>

export default {

}
</script>

 <style>
 body{
   font-family: 'Russo One', sans-serif;
 }
 </style>
