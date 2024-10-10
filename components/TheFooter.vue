<template>
    <footer class="bg-[#f8f9fc] text-[#0e101b] py-6 px-40">
        <div class="layout-content-container flex flex-col max-w-[960px] mx-auto">

            <!-- Footer Top Section -->
            <div class="flex flex-wrap justify-between items-start gap-8 pb-6 border-b border-[#d0d3e7]">
                <!-- Company Information -->
                <div class="flex flex-col gap-3">
                    <p class="text-2xl font-bold">Ummq Cleaning Services</p>
                    <p class="text-sm text-[#4e5997]">
                        Professional cleaning services for homes and offices. Quality service, every time.
                    </p>
                </div>

                <!-- Social Media Links -->
                <div class="flex flex-col gap-2">
                    <p class="text-lg font-bold">Follow Us</p>
                    <div class="flex gap-4">
                        <a href="https://www.instagram.com/ummq.sa?igsh=MWd4emF4Mnl2YmprdA==/" target="_blank">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png"
                                alt="Instagram Icon" class="w-6 h-6">
                        </a>
                        <a href="https://www.snapchat.com/add/ummqsa?sender_web_id=f4a05cd9-9231-4341-afdb-b89c144a16c3&device_type=desktop&is_copy_url=true/"
                            target="_blank">
                            <img src="https://upload.wikimedia.org/wikipedia/en/c/c4/Snapchat_logo.svg"
                                alt="Snapchat Icon" class="w-6 h-6">
                        </a>
                        <a href="https://www.tiktok.com/@ummq.saa?_t=8kSB4FkN7g2&_r=1/" target="_blank">
                            <img src="https://upload.wikimedia.org/wikipedia/en/a/a9/TikTok_logo.svg" alt="TikTok Icon"
                                class="w-6 h-6">
                        </a>
                        <a href="https://twitter.com/ummq_sa/" target="_blank">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/c/ce/X_logo_2023.svg" alt="X Icon"
                                class="w-6 h-6">
                        </a>
                        <a href="https://www.facebook.com/profile.php?id=61554713859126&mibextid=ZbWKwL/"
                            target="_blank">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg"
                                alt="Facebook Icon" class="w-6 h-6">
                        </a>
                    </div>
                </div>
            </div>

            <!-- Footer Bottom Section -->
            <div class="flex justify-between items-center pt-4 text-sm text-[#4e5997]">
                <p>&copy; 2024 Ummq Cleaning Services. All rights reserved.</p>
                <NuxtLink
                    class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 @[480px]:h-12 @[480px]:px-5 bg-[#e7e9f3] text-[#0e101b] text-sm font-bold leading-normal tracking-[0.015em] @[480px]:text-base @[480px]:font-bold @[480px]:leading-normal @[480px]:tracking-[0.015em]"
                    to="/login">
                    <span class="truncate">Log in</span>
                </NuxtLink>
            </div>
        </div>
    </footer>
</template>

<script setup>
</script>
