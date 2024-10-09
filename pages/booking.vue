<template>
    <div class="relative flex size-full min-h-screen flex-col bg-white group/design-root overflow-x-hidden"
        style='--checkbox-tick-svg: url(&apos;data:image/svg+xml,%3csvg viewBox=%270 0 16 16%27 fill=%27rgb(255,255,255)%27 xmlns=%27http://www.w3.org/2000/svg%27%3e%3cpath d=%27M12.207 4.793a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0l-2-2a1 1 0 011.414-1.414L6.5 9.086l4.293-4.293a1 1 0 011.414 0z%27/%3e%3c/svg%3e&apos;); font-family: "Public Sans", "Noto Sans", sans-serif;'>
        <div class="layout-container flex h-full grow flex-col">

            <div class="px-40 flex flex-1 justify-center py-5">
                <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
                    <div class="flex flex-wrap justify-between gap-3 p-4">
                        <p class="text-[#111218] tracking-light text-[32px] font-bold leading-tight min-w-72">Book an
                            appointment</p>
                    </div>
                    <h1
                        class="text-[#111218] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 text-left pb-3 pt-5">
                        What type of cleaning do you need?</h1>
                    <div class="flex flex-wrap gap-3 p-4">
                        <label
                            class="text-sm font-medium leading-normal flex items-center justify-center rounded-xl border border-[#dbdde6] px-4 h-11 text-[#111218] has-[:checked]:border-[3px] has-[:checked]:px-3.5 has-[:checked]:border-[#5068f1] relative cursor-pointer">
                            House
                            <input type="radio" class="invisible absolute"
                                name="b4306834-8fcb-4f66-8194-10effeac19b6" />
                        </label>
                        <label
                            class="text-sm font-medium leading-normal flex items-center justify-center rounded-xl border border-[#dbdde6] px-4 h-11 text-[#111218] has-[:checked]:border-[3px] has-[:checked]:px-3.5 has-[:checked]:border-[#5068f1] relative cursor-pointer">
                            Apartment
                            <input type="radio" class="invisible absolute"
                                name="b4306834-8fcb-4f66-8194-10effeac19b6" />
                        </label>
                        <label
                            class="text-sm font-medium leading-normal flex items-center justify-center rounded-xl border border-[#dbdde6] px-4 h-11 text-[#111218] has-[:checked]:border-[3px] has-[:checked]:px-3.5 has-[:checked]:border-[#5068f1] relative cursor-pointer">
                            Office
                            <input type="radio" class="invisible absolute"
                                name="b4306834-8fcb-4f66-8194-10effeac19b6" />
                        </label>
                        <label
                            class="text-sm font-medium leading-normal flex items-center justify-center rounded-xl border border-[#dbdde6] px-4 h-11 text-[#111218] has-[:checked]:border-[3px] has-[:checked]:px-3.5 has-[:checked]:border-[#5068f1] relative cursor-pointer">
                            Roof
                            <input type="radio" class="invisible absolute"
                                name="b4306834-8fcb-4f66-8194-10effeac19b6" />
                        </label>
                        <label
                            class="text-sm font-medium leading-normal flex items-center justify-center rounded-xl border border-[#dbdde6] px-4 h-11 text-[#111218] has-[:checked]:border-[3px] has-[:checked]:px-3.5 has-[:checked]:border-[#5068f1] relative cursor-pointer">
                            External interfaces
                            <input type="radio" class="invisible absolute"
                                name="b4306834-8fcb-4f66-8194-10effeac19b6" />
                        </label>
                    </div>
                    <h1
                        class="text-[#111218] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 text-left pb-3 pt-5">
                        When do you want us to come?</h1>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
                        <label class="flex flex-col min-w-40 flex-1">
                            <p class="text-[#111218] text-base font-medium leading-normal pb-2">Date</p>
                            <input placeholder="MM/DD/YYYY"
                                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111218] focus:outline-0 focus:ring-0 border border-[#dbdde6] bg-white focus:border-[#dbdde6] h-14 placeholder:text-[#616789] p-[15px] text-base font-normal leading-normal"
                                value="" />
                        </label>
                        <label class="flex flex-col min-w-40 flex-1">
                            <p class="text-[#111218] text-base font-medium leading-normal pb-2">Time</p>
                            <input placeholder="HH:MM AM"
                                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111218] focus:outline-0 focus:ring-0 border border-[#dbdde6] bg-white focus:border-[#dbdde6] h-14 placeholder:text-[#616789] p-[15px] text-base font-normal leading-normal"
                                value="" />
                        </label>
                    </div>
                    <h1
                        class="text-[#111218] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 text-left pb-3 pt-5">
                        How can we contact you?</h1>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
                        <label class="flex flex-col min-w-40 flex-1">
                            <input placeholder="Full Name"
                                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111218] focus:outline-0 focus:ring-0 border border-[#dbdde6] bg-white focus:border-[#dbdde6] h-14 placeholder:text-[#616789] p-[15px] text-base font-normal leading-normal"
                                value="" />
                        </label>
                    </div>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
                        <label class="flex flex-col min-w-40 flex-1">
                            <input placeholder="Phone Number"
                                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111218] focus:outline-0 focus:ring-0 border border-[#dbdde6] bg-white focus:border-[#dbdde6] h-14 placeholder:text-[#616789] p-[15px] text-base font-normal leading-normal"
                                value="" />
                        </label>
                    </div>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3">
                        <label class="flex flex-col min-w-40 flex-1">
                            <input placeholder="Email Address"
                                class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-xl text-[#111218] focus:outline-0 focus:ring-0 border border-[#dbdde6] bg-white focus:border-[#dbdde6] h-14 placeholder:text-[#616789] p-[15px] text-base font-normal leading-normal"
                                value="" />
                        </label>
                    </div>
                    <div class="px-4">
                        <label class="flex gap-x-3 py-3 flex-row">
                            <input type="checkbox"
                                class="h-5 w-5 rounded border-[#dbdde6] border-2 bg-transparent text-[#5068f1] checked:bg-[#5068f1] checked:border-[#5068f1] checked:bg-[image:--checkbox-tick-svg] focus:ring-0 focus:ring-offset-0 focus:border-[#dbdde6] focus:outline-none"
                                checked="" />
                            <p class="text-[#111218] text-base font-normal leading-normal">I understand that this is an
                                appointment request, and not a confirmed booking</p>
                        </label>
                        <label class="flex gap-x-3 py-3 flex-row">
                            <input type="checkbox"
                                class="h-5 w-5 rounded border-[#dbdde6] border-2 bg-transparent text-[#5068f1] checked:bg-[#5068f1] checked:border-[#5068f1] checked:bg-[image:--checkbox-tick-svg] focus:ring-0 focus:ring-offset-0 focus:border-[#dbdde6] focus:outline-none"
                                checked="" />
                            <p class="text-[#111218] text-base font-normal leading-normal">I certify that I am 18 years
                                of age or older</p>
                        </label>
                        <label class="flex gap-x-3 py-3 flex-row">
                            <input type="checkbox"
                                class="h-5 w-5 rounded border-[#dbdde6] border-2 bg-transparent text-[#5068f1] checked:bg-[#5068f1] checked:border-[#5068f1] checked:bg-[image:--checkbox-tick-svg] focus:ring-0 focus:ring-offset-0 focus:border-[#dbdde6] focus:outline-none" />
                            <p class="text-[#111218] text-base font-normal leading-normal">I have read and agree to the
                                Terms of Service and Privacy Policy</p>
                        </label>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<script setup>
</script>