<template>
    <div class="relative flex size-full min-h-screen flex-col bg-[#FFFFFF] group/design-root overflow-x-hidden"
        style='font-family: "Plus Jakarta Sans", "Noto Sans", sans-serif;'>
        <div class="layout-container flex h-full grow flex-col">
            <header
                class="flex items-center justify-between whitespace-nowrap border-b border-solid border-b-[#F4EFE6] px-10 py-3">
                <div class="flex items-center gap-4 text-[#1C160C]">
                    <div class="size-4">
                        <svg viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M6 6H42L36 24L42 42H6L12 24L6 6Z" fill="currentColor"></path>
                        </svg>
                    </div>
                    <h2 class="text-[#1C160C] text-lg font-bold leading-tight tracking-[-0.015em]">Your Product Name
                    </h2>
                </div>
                <div class="flex flex-1 justify-end gap-8">
                    <div class="flex items-center gap-9">
                        <a class="text-[#1C160C] text-sm font-medium leading-normal" href="#">Home</a>
                        <a class="text-[#1C160C] text-sm font-medium leading-normal" href="#">Features</a>
                        <a class="text-[#1C160C] text-sm font-medium leading-normal" href="#">Pricing</a>
                    </div>
                    <div class="flex gap-2">
                        <button
                            class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-[#019863] text-[#FFFFFF] text-sm font-bold leading-normal tracking-[0.015em]">
                            <span class="truncate">Login</span>
                        </button>
                        <button
                            class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-10 px-4 bg-[#F4EFE6] text-[#1C160C] text-sm font-bold leading-normal tracking-[0.015em]">
                            <span class="truncate">Sign Up</span>
                        </button>
                    </div>
                    <div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full size-10"
                        style='background-image: url("https://cdn.usegalileo.ai/stability/245cd562-4b85-4b68-9ade-bdc68506fdf6.png");'>
                    </div>
                </div>
            </header>
            <div class="gap-1 px-6 flex flex-1 justify-center py-5">
                <div class="layout-content-container flex flex-col max-w-[920px] flex-1">
                    <div class="flex flex-wrap justify-between gap-3 p-4">
                        <p class="text-[#1C160C] text-4xl font-black leading-tight tracking-[-0.033em] min-w-72">Create
                            Account</p>
                    </div>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
                        <label class="flex flex-col min-w-40 flex-1">
                            <input placeholder="Enter your email"
                                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#1C160C] focus:outline-0 focus:ring-0 border border-[#E9DFCE] bg-[#FFFFFF] focus:border-[#E9DFCE] h-14 placeholder:text-[#A18249] p-[15px] text-base font-normal leading-normal"
                                value="" />
                        </label>
                    </div>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
                        <label class="flex flex-col min-w-40 flex-1">
                            <input placeholder="Enter your phone no"
                                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#1C160C] focus:outline-0 focus:ring-0 border border-[#E9DFCE] bg-[#FFFFFF] focus:border-[#E9DFCE] h-14 placeholder:text-[#A18249] p-[15px] text-base font-normal leading-normal"
                                value="" />
                        </label>
                    </div>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
                        <label class="flex flex-col min-w-40 flex-1">
                            <input placeholder="Enter your password"
                                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#1C160C] focus:outline-0 focus:ring-0 border border-[#E9DFCE] bg-[#FFFFFF] focus:border-[#E9DFCE] h-14 placeholder:text-[#A18249] p-[15px] text-base font-normal leading-normal"
                                value="" />
                        </label>
                    </div>
                    <div class="flex px-4 py-3 justify-center">
                        <button
                            class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-12 px-5 flex-1 bg-[#019863] text-[#FFFFFF] text-base font-bold leading-normal tracking-[0.015em]">
                            <span class="truncate">Create Account</span>
                        </button>
                    </div>
                    <p class="text-[#A18249] text-sm font-normal leading-normal pb-3 pt-1 px-4 text-center underline">
                        Already have an account? Sign-In</p>
                </div>
                <div class="layout-content-container flex flex-col w-[360px]">
                    <div class="@container">
                        <div class="@[480px]:px-4 @[480px]:py-3">
                            <div class="w-full bg-center bg-no-repeat bg-cover flex flex-col justify-end overflow-hidden bg-[#FFFFFF] @[480px]:rounded-xl min-h-80"
                                style='background-image: url("https://cdn.usegalileo.ai/sdxl10/4d4c6867-54fa-41d8-b0ec-ea72dc1dd3da.png");'>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

// const login = async () => {
//   try {
//     const { data, error: authError } = identifier.value.includes('@')
//       ? await supabase.auth.signInWithPassword({ email: identifier.value, password: password.value })
//       : await supabase.auth.signInWithPassword({ phone: identifier.value, password: password.value })

//     if (authError) throw authError
//     // Handle successful login
//   } catch (e) {
//     error.value = e.message
//   }
// }
</script>