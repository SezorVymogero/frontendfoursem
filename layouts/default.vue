<style>
@import url('https://fonts.googleapis.com/css2?family=Jersey+15&display=swap');

.jersey-font {
  font-family: 'Jersey 15', sans-serif;
}
</style>
<template>
    <div class="background">
      <header class="flex flex-row w-full bg-[#49627e] border-b-[7px] border-t-[7px] border-[#374151] max-sm:justify-between max-sm:relative">
        <div class="basis-1/4 items-center justify-start px-8 min-w-40 max-sm:basis-auto">
          <NuxtLink to="/">
            <img src="assets/images/Nebula_logo_full.svg" class="w-112 h-16 hover:bg-[#1b2028] p-2">
          </NuxtLink>
        </div>
        <div class="basis-1/4 max-sm:basis-auto"></div>
        <nav class="basis-1/2 flex flex-row items-center justify-end px-8 gap-4 max-sm:basis-auto max-sm:absolute max-sm:top-full max-sm:w-full max-sm:justify-center max-sm:flex-col max-sm:gap-0 max-sm:bg-white mas-sm:px-0">
          <div class="my-auto p-2 hover:bg-gray-500 hover:text-white max-sm:w-full max-sm:text-center max-sm:px-0 max-sm:pb-0">Labs
            <div class="flex flex-col absolute top-full bg-white text-black w-56 text-center max-sm:relative max-sm:w-full max-sm:bg-red-100">
              <NuxtLink to="/LogIn" class="jersey-font my-auto text-5xl text-[#83dbea] p-2 hover:text-[#49627e] hover:bg-[#aed4fd] max-sm:w-full max-sm:border-b-2 max-sm:border-black max-sm:text-center">Lab 3</NuxtLink>
              <NuxtLink to="/LogIn" class="jersey-font my-auto text-5xl text-[#83dbea] p-2 hover:text-[#49627e] hover:bg-[#aed4fd] max-sm:w-full max-sm:border-b-2 max-sm:border-black max-sm:text-center">Lab 4</NuxtLink>
              <NuxtLink to="/LogIn" class="jersey-font my-auto text-5xl text-[#83dbea] p-2 hover:text-[#49627e] hover:bg-[#aed4fd] max-sm:w-full max-sm:border-b-2 max-sm:border-black max-sm:text-center">Lab 5</NuxtLink>
              <NuxtLink to="/LogIn" class="jersey-font my-auto text-5xl text-[#83dbea] p-2 hover:text-[#49627e] hover:bg-[#aed4fd] max-sm:w-full max-sm:border-b-2 max-sm:border-black max-sm:text-center">Lab 6</NuxtLink>
            </div>
          </div>
          <NuxtLink to="/LogIn" class="jersey-font my-auto text-5xl text-[#83dbea] p-2 hover:text-[#49627e] hover:bg-[#aed4fd] max-sm:w-full max-sm:border-b-2 max-sm:border-black max-sm:text-center">Log In</NuxtLink>
          <NuxtLink to="/LogOut" class="jersey-font my-auto text-5xl text-[#83dbea] p-2 hover:text-[#49627e] hover:bg-[#aed4fd] max-sm:w-full max-sm:border-b-2 max-sm:border-black max-sm:text-center">Log Out</NuxtLink>
        </nav>
      </header>
      <main class="p-5 flex h-screen">
        <slot />
      </main>
      <footer class="flex flex-row w-full bg-[#49627e] border-b-[7px] border-t-[7px] border-[#374151] items-center justify-center px-4 py-2 gap-4">
        <a href="https://www.youtube.com/"><img src="assets/images/youtube_logo.svg" class="w-16 h-16 hover:bg-[#1b2028]"></a>
        <a href="https://github.com/SezorVymogero"><img src="assets/images/github_logo.svg" class="w-16 h-16 hover:bg-[#1b2028]"></a>
      </footer>
    </div>
  </template>
  
  <style>
  .background {
    background: url("assets/images/Stars_ver3.webp") repeat;
    background-size: 75%;
    image-rendering: pixelated;
  }
  </style>
  