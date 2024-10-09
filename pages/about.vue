<template>
  <div class="relative flex size-full min-h-screen flex-col bg-[#f8f9fc] group/design-root overflow-x-hidden"
    style='font-family: "Public Sans", "Noto Sans", sans-serif;'>
    <div class="layout-container flex h-full grow flex-col">
      <div class="px-40 flex flex-1 justify-center py-5">
        <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
          <div class="@container">
            <div class="flex flex-col gap-6 px-4 py-10 @[480px]:gap-8 @[864px]:flex-row">
              <div
                class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl @[480px]:h-auto @[480px]:min-w-[400px] @[864px]:w-full"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/ea468b77-f07c-4328-bd3f-eb58e2218312.png");'>
              </div>
              <div class="flex flex-col gap-6 @[480px]:min-w-[400px] @[480px]:gap-8 @[864px]:justify-center">
                <div class="flex flex-col gap-2 text-left">
                  <h1
                    class="text-[#0e101b] text-4xl font-black leading-tight tracking-[-0.033em] @[480px]:text-5xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em]">
                    Deep clean, every time
                  </h1>
                  <h2
                    class="text-[#0e101b] text-sm font-normal leading-normal @[480px]:text-base @[480px]:font-normal @[480px]:leading-normal">
                    At UMQ, we're committed to using the safest certified materials for our clients. We're dedicated
                    to providing deep cleaning services at affordable prices. Our
                    mission is to provide the best possible service to our clients, and we're always looking for ways
                    to improve.
                  </h2>
                </div>
                <label class="flex flex-col min-w-40 h-14 w-full max-w-[480px] @[480px]:h-16">
                  <div class="flex w-full flex-1 items-stretch rounded-xl h-full">
                    <div
                      class="text-[#4e5997] flex border-none bg-[#e7e9f3] items-center justify-center pl-4 rounded-l-xl border-r-0"
                      data-icon="MagnifyingGlass" data-size="20px" data-weight="regular">
                      <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor"
                        viewBox="0 0 256 256">
                        <path
                          d="M229.66,218.34l-50.07-50.06a88.11,88.11,0,1,0-11.31,11.31l50.06,50.07a8,8,0,0,0,11.32-11.32ZM40,112a72,72,0,1,1,72,72A72.08,72.08,0,0,1,40,112Z">
                        </path>
                      </svg>
                    </div>
                    <input placeholder="Enter your email address"
                      class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#0e101b] focus:outline-0 focus:ring-0 border-none bg-[#e7e9f3] focus:border-none h-full placeholder:text-[#4e5997] px-4 rounded-r-none border-r-0 pr-2 rounded-l-none border-l-0 pl-2 text-sm font-normal leading-normal @[480px]:text-base @[480px]:font-normal @[480px]:leading-normal"
                      value="" />
                    <div
                      class="flex items-center justify-center rounded-r-xl border-l-0 border-none bg-[#e7e9f3] pr-2">
                      <button
                        class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 @[480px]:h-12 @[480px]:px-5 bg-[#556bec] text-[#f8f9fc] text-sm font-bold leading-normal tracking-[0.015em] @[480px]:text-base @[480px]:font-bold @[480px]:leading-normal @[480px]:tracking-[0.015em]">
                        <span class="truncate">Sign Up</span>
                      </button>
                    </div>
                  </div>
                </label>
              </div>
            </div>
          </div>
          <div class="flex flex-col gap-10 px-4 py-10 @container">
            <h1
              class="text-[#0e101b] tracking-light text-[32px] font-bold leading-tight @[480px]:text-4xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em] max-w-[720px]">
              Why choose us
            </h1>
          </div>
          <h2 class="text-[#0e101b] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5">Our
            History</h2>
          <div class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3 p-4">
            <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
              <div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full w-10 shrink-0"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/ca743263-3f16-4969-95c3-2382abb8c22f.png");'>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#0e101b] text-base font-bold leading-tight">2010</h2>
                <p class="text-[#4e5997] text-sm font-normal leading-normal">Founded</p>
              </div>
            </div>
            <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
              <div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full w-10 shrink-0"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/8b50cbb0-8282-4651-8f8c-50bd6177e7b6.png");'>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#0e101b] text-base font-bold leading-tight">2012</h2>
                <p class="text-[#4e5997] text-sm font-normal leading-normal">Awarded Best Cleaning Service</p>
              </div>
            </div>
            <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
              <div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full w-10 shrink-0"
                style='background-image: url("https://cdn.usegalileo.ai/stability/65a7a091-fb05-491d-8038-9cb115f366bf.png");'>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#0e101b] text-base font-bold leading-tight">2014</h2>
                <p class="text-[#4e5997] text-sm font-normal leading-normal">Expanded to More Locations</p>
              </div>
            </div>
            <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
              <div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full w-10 shrink-0"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/89d974f2-b3b4-4795-bf27-bcb3796d5314.png");'>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#0e101b] text-base font-bold leading-tight">2016</h2>
                <p class="text-[#4e5997] text-sm font-normal leading-normal">Launched UMQ Eco-Friendly Line</p>
              </div>
            </div>
            <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
              <div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full w-10 shrink-0"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/f6ca8e3e-eb11-4778-957b-2d1e42960008.png");'>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#0e101b] text-base font-bold leading-tight">2018</h2>
                <p class="text-[#4e5997] text-sm font-normal leading-normal">Reached 10,000 Happy Clients</p>
              </div>
            </div>
            <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
              <div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full w-10 shrink-0"
                style='background-image: url("https://cdn.usegalileo.ai/stability/01822f55-8c2f-4213-a535-9c5055a86955.png");'>
              </div>
              <div class="flex flex-col gap-1">
                <h2 class="text-[#0e101b] text-base font-bold leading-tight">2020</h2>
                <p class="text-[#4e5997] text-sm font-normal leading-normal">Launched UMQ Cleaning Academy</p>
              </div>
            </div>
          </div>
          <h2 class="text-[#0e101b] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5">Our Team
          </h2>
          <div class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3 p-4">
            <div class="flex flex-col gap-3">
              <div class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-xl"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/90d72973-31dd-4027-bfd6-7247440fa986.png");'>
              </div>
            </div>
            <div class="flex flex-col gap-3">
              <div class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-xl"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/264339a8-0c9a-493b-9eac-4981dc6ac98c.png");'>
              </div>
            </div>
            <div class="flex flex-col gap-3">
              <div class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-xl"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/a5e946db-767b-48a3-914b-49328bb6593d.png");'>
              </div>
            </div>
            <div class="flex flex-col gap-3">
              <div class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-xl"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/5836a34b-cfe0-4048-9640-b255d632cc18.png");'>
              </div>
            </div>
            <div class="flex flex-col gap-3">
              <div class="w-full bg-center bg-no-repeat aspect-square bg-cover rounded-xl"
                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/5078fb87-d069-4762-a348-3124881d2c05.png");'>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>
