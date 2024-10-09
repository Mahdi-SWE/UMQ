<template>
  <div class="relative flex min-h-screen flex-col overflow-x-hidden"
    style="font-family: 'Public Sans', 'Noto Sans', sans-serif">
    <div class="layout-container flex h-full grow flex-col">
      <div class="px-40 flex flex-1 justify-center py-5">
        <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
          <div class="@container">
            <div class="@[480px]:p-4">
              <div
                class="flex min-h-[480px] flex-col gap-6 bg-cover bg-center bg-no-repeat @[480px]:gap-8 @[480px]:rounded-xl items-start justify-end px-4 pb-10 @[480px]:px-10"
                style="
                  background-image: linear-gradient(
                      rgba(0, 0, 0, 0.1) 0%,
                      rgba(0, 0, 0, 0.4) 100%
                    ),
                    url('https://cdn.usegalileo.ai/sdxl10/8f54814a-fe37-4182-b3a6-f222985466b4.png');
                ">
                <div class="flex flex-col gap-2 text-left">
                  <h1
                    class="text-white text-4xl font-black leading-tight tracking-[-0.033em] @[480px]:text-5xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em]">
                    Professional cleaning services for your home and office.
                  </h1>
                  <h2
                    class="text-white text-sm font-normal leading-normal @[480px]:text-base @[480px]:font-normal @[480px]:leading-normal">
                    We use the latest cleaning techniques and eco-friendly
                    materials to ensure the health and safety of your family and
                    employees.
                  </h2>
                </div>
                <div class="flex-wrap gap-3 flex">
                  <NuxtLink
                    class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 bg-[#556bec] text-[#f8f9fc] text-sm font-bold leading-normal tracking-[0.015em]"
                    to="/booking">
                    <span class="truncate">Book Now</span>
                  </NuxtLink>
                  <NuxtLink
                    class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 @[480px]:h-12 @[480px]:px-5 bg-[#e7e9f3] text-[#0e101b] text-sm font-bold leading-normal tracking-[0.015em] @[480px]:text-base @[480px]:font-bold @[480px]:leading-normal @[480px]:tracking-[0.015em]" to="/about">
                    <span class="truncate">Learn More</span>
                  </NuxtLink>
                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-col gap-10 px-4 py-10 @container">
            <h1
              class="text-[#0e101b] tracking-light text-[32px] font-bold leading-tight @[480px]:text-4xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em] max-w-[720px]">
              Our Services
            </h1>
            <div class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3">
              <div class="flex flex-col gap-3 pb-3">
                <div class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl" style="
                    background-image: url('https://cdn.usegalileo.ai/stability/16d7604a-5e01-4262-81fb-30300ae506ec.png');
                  "></div>
                <div>
                  <p class="text-[#0e101b] text-base font-medium leading-normal">
                    House Cleaning
                  </p>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    Our professional cleaners will make your house sparkle,
                    leaving you with more time to do the things you love.
                  </p>
                </div>
              </div>
              <div class="flex flex-col gap-3 pb-3">
                <div class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl" style="
                    background-image: url('https://cdn.usegalileo.ai/sdxl10/7f6df5e6-8ac6-431e-95ec-9f4a34c77615.png');
                  "></div>
                <div>
                  <p class="text-[#0e101b] text-base font-medium leading-normal">
                    Apartment Cleaning
                  </p>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    We offer a range of apartment cleaning services to suit your
                    needs. Let us take care of the cleaning so you can relax and
                    enjoy your space.
                  </p>
                </div>
              </div>
              <div class="flex flex-col gap-3 pb-3">
                <div class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-xl" style="
                    background-image: url('https://cdn.usegalileo.ai/sdxl10/bbdc3dd5-9fbd-42f6-8bc2-c40d1fc376c4.png');
                  "></div>
                <div>
                  <p class="text-[#0e101b] text-base font-medium leading-normal">
                    Office Cleaning
                  </p>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    We provide high-quality office cleaning services
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="flex flex-col gap-10 px-4 py-10 @container">
            <h1
              class="text-[#0e101b] tracking-light text-[32px] font-bold leading-tight @[480px]:text-4xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em] max-w-[720px]">
              Why Choose UMQ Cleaning Services?
            </h1>
            <div class="grid grid-cols-[repeat(auto-fit,minmax(158px,1fr))] gap-3 p-0">
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="ShieldCheck" data-size="24px" data-weight="regular">
                  <ShieldCheckIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Safe & Effective
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    Our cleaning products are safe and effective. They have
                    international certificates and are suitable for use in
                    homes, offices, and commercial environments.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="HandHeart" data-size="24px" data-weight="regular">
                  <HandHeartIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Eco-Friendly
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    We use eco-friendly cleaning products that are safe for your
                    family and the environment. Our cleaners are trained to use
                    these products effectively, ensuring a thorough and hygienic
                    clean.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="Truck" data-size="24px" data-weight="regular">
                  <TruckIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Convenient
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    We offer convenient online booking and flexible scheduling
                    options to suit your needs. Whether you need a one-time
                    clean, regular service, or a deep clean, we've got you
                    covered.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="Clock" data-size="24px" data-weight="regular">
                  <ClockIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Flexible
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    Our cleaning services are flexible, so you can customize
                    your cleaning plan to suit your needs and budget. Whether
                    you need a basic clean or a detailed deep clean, our
                    experienced team will deliver exceptional results.
                  </p>
                </div>
              </div>
              <div class="flex flex-1 gap-3 rounded-lg border border-[#d0d3e7] bg-[#f8f9fc] p-4 flex-col">
                <div class="text-[#0e101b]" data-icon="Tag" data-size="24px" data-weight="regular">
                  <TagIcon />
                </div>
                <div class="flex flex-col gap-1">
                  <h2 class="text-[#0e101b] text-base font-bold leading-tight">
                    Affordable
                  </h2>
                  <p class="text-[#4e5997] text-sm font-normal leading-normal">
                    We offer affordable cleaning services with transparent
                    pricing and no hidden fees. Our goal is to provide
                    high-quality cleaning services that are accessible to
                    everyone.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { createClient } from "@supabase/supabase-js";
const supabase = createClient(
  "https://tcyirnghbyqsfezcimop.supabase.co",
  "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InRjeWlybmdoYnlxc2ZlemNpbW9wIiwicm9sZSI6ImFub24iLCJpYXQiOjE3MjA3MDI2MjMsImV4cCI6MjAzNjI3ODYyM30.rw0g0U7TLk_x6lyOjw0BWhZXJdz5aVrPTgqU0qi-AJU"
);
const countries = ref([]);

async function getCountries() {
  const { data } = await supabase.from("countries").select();
  countries.value = data;
}

onMounted(() => {
  // getCountries()
});
</script>
