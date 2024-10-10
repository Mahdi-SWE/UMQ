<template>
    <div class="relative flex min-h-screen flex-col overflow-x-hidden"
        style='--checkbox-tick-svg: url(&apos;data:image/svg+xml,%3csvg viewBox=%270 0 16 16%27 fill=%27rgb(255,255,255)%27 xmlns=%27http://www.w3.org/2000/svg%27%3e%3cpath d=%27M12.207 4.793a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0l-2-2a1 1 0 011.414-1.414L6.5 9.086l4.293-4.293a1 1 0 011.414 0z%27/%3e%3c/svg%3e&apos;); font-family: "Public Sans", "Noto Sans", sans-serif;'>
        <div class="flex h-full items-center justify-center">
            <div class="layout-content-container flex flex-col w-full max-w-[512px] px-4 py-5">
                <h1 class="text-[#111218] text-[22px] font-bold leading-tight tracking-[-0.015em] text-left pb-3">
                    Welcome back to UMQ
                </h1>
                <p class="text-[#111218] text-base font-normal leading-normal pb-3 pt-1">
                    Please enter your username and password
                </p>
                <div class="flex flex-wrap items-end gap-4">
                    <label class="flex flex-col flex-1">
                        <p class="text-[#111218] text-base font-medium leading-normal pb-2">Username</p>
                        <input placeholder="Username"
                            class="form-input flex w-full rounded-xl border border-[#dbdde6] bg-white h-14 placeholder:text-[#616789] p-[15px] text-base font-normal leading-normal focus:border-[#dbdde6] focus:outline-0"
                        />
                    </label>
                </div>
                <div class="flex flex-wrap items-end gap-4 pt-3">
                    <label class="flex flex-col flex-1">
                        <p class="text-[#111218] text-base font-medium leading-normal pb-2">Password</p>
                        <input placeholder="Password"
                            class="form-input flex w-full rounded-xl border border-[#dbdde6] bg-white h-14 placeholder:text-[#616789] p-[15px] text-base font-normal leading-normal focus:border-[#dbdde6] focus:outline-0"
                        />
                    </label>
                </div>
                <!-- <div class="py-3">
                    <label class="flex items-center gap-x-3">
                        <input type="checkbox"
                            class="h-5 w-5 rounded border-[#dbdde6] border-2 bg-transparent text-[#5068f1] checked:bg-[#5068f1] focus:ring-0 focus:outline-none" />
                        <p class="text-[#111218] text-base font-normal leading-normal">Remember me</p>
                    </label>
                </div> -->
                <div class="flex py-3">
                    <button
                        class="flex min-w-[84px] w-full cursor-pointer items-center justify-center rounded-xl h-10 bg-[#5068f1] text-white text-sm font-bold">
                        <span class="truncate">Log in</span>
                    </button>
                </div>
                <!-- <p class="text-[#616789] text-sm font-normal leading-normal pb-3 text-center underline">
                    Forgot your password?
                </p> -->
            </div>
        </div>
    </div>
</template>

<script setup>
</script>
