<template>
  <div class="flex items-center justify-between bg-white shadow-md py-4 px-10">
    <!-- Logo Section -->
    <div class="flex items-center gap-4 text-gray-900">
      <!-- Use the logo image from the public folder -->
      <div class="h-12 w-12">
        <img src="/UMQ.png" alt="UMQ Cleaning Services Logo" class="h-full w-full object-contain" />
      </div>
      <h2 class="text-lg font-bold">UMQ Cleaning Services</h2>
    </div>

    <!-- Navigation Links Section -->
    <div class="flex flex-1 justify-end gap-8">
      <nav class="flex items-center gap-9">
        <NuxtLink class="text-[#0e101b] text-sm font-medium leading-normal" to="/"> Home </NuxtLink>
        <NuxtLink class="text-[#0e101b] text-sm font-medium leading-normal" to="/contact"> Contact us </NuxtLink>
        <NuxtLink class="text-[#0e101b] text-sm font-medium leading-normal" to="/about"> About us </NuxtLink>
      </nav>
      <NuxtLink
        class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 bg-[#556bec] text-[#f8f9fc] text-sm font-bold leading-normal tracking-[0.015em]" to="/booking">
        <span class="truncate">Book Now</span>
      </NuxtLink>
    </div>
    

    <!-- Mobile Menu Button -->
    <button class="md:hidden flex items-center justify-center text-gray-900">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
      </svg>
    </button>
  </div>
</template>

