<template>
    <div class="relative flex min-h-screen flex-col items-center justify-center bg-white overflow-x-hidden"
        style="font-family: 'Public Sans', 'Noto Sans', sans-serif">
        <div class="layout-container flex h-full grow flex-col items-center justify-center">
            <div class="flex flex-col max-w-[960px] w-full items-center justify-center">
                <div class="text-center py-5">
                    <h1 class="text-[#111218] text-[32px] font-bold">Book an Appointment</h1>
                </div>

                <!-- Type of Cleaning Section -->
                <div class="w-full px-4 py-5">
                    <h2 class="text-[#111218] text-[22px] font-bold pb-3">What type of cleaning do you need?</h2>
                    <div class="flex flex-wrap justify-center gap-3 p-4">
                        <label v-for="option in ['House', 'Apartment', 'Office', 'Roof', 'External interfaces']"
                            :key="option"
                            class="text-sm font-medium flex items-center justify-center rounded-xl border border-[#dbdde6] px-4 h-11 text-[#111218] relative cursor-pointer"
                            :class="{ 'border-[#5068f1] bg-[#f1f3fe]': form.cleaningType === option }">
                            {{ option }}
                            <input type="radio" class="absolute left-0 opacity-0 cursor-pointer" name="cleaningType"
                                :value="option" v-model="form.cleaningType" />
                        </label>
                    </div>
                </div>

                <!-- Date and Time Section -->
                <div class="w-full px-4 py-5">
                    <h2 class="text-[#111218] text-[22px] font-bold pb-3">When do you want the appointment?</h2>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3 justify-center">
                        <label class="flex flex-col min-w-40 flex-1">
                            <p class="text-[#111218] text-base font-medium leading-normal pb-2">Choose a date</p>
                            <VueDatePicker v-model="form.date" no-today auto-apply :enable-time-picker="false"
                                :min-date="new Date()"
                                :max-date="new Date((new Date()).getTime() + (60 * 24 * 60 * 60 * 1000))"
                                placeholder="Choose a day">
                            </VueDatePicker>
                        </label>
                    </div>
                </div>

                <!-- Contact Information Section -->
                <div class="w-full px-4 py-5">
                    <h2 class="text-[#111218] text-[22px] font-bold pb-3">How can we contact you?</h2>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3 justify-center">
                        <label class="flex flex-col min-w-40 flex-1">
                            <p class="text-[#111218] text-base font-medium leading-normal pb-2">Enter your name</p>
                            <input placeholder="Full Name"
                                class="form-input w-full rounded-xl text-[#111218] border border-[#dbdde6] bg-white p-[15px] text-base font-normal leading-normal"
                                v-model="form.fullName" />
                        </label>
                    </div>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3 justify-center">
                        <label class="flex flex-col min-w-40 flex-1">
                            <p class="text-[#111218] text-base font-medium leading-normal pb-2">Enter your phone number</p>
                            <input type="number" placeholder="0500000000"
                                class="form-input w-full rounded-xl text-[#111218] border border-[#dbdde6] bg-white p-[15px] text-base font-normal leading-normal"
                                v-model="form.phone" />
                        </label>
                    </div>
                    <div class="flex max-w-[480px] flex-wrap items-end gap-4 px-4 py-3 justify-center">
                        <label class="flex flex-col min-w-40 flex-1">
                            <p class="text-[#111218] text-base font-medium leading-normal pb-2">Enter your email</p>
                            <input placeholder="example@email.com"
                                class="form-input w-full rounded-xl text-[#111218] border border-[#dbdde6] bg-white p-[15px] text-base font-normal leading-normal"
                                v-model="form.email" />
                        </label>
                    </div>
                </div>

                <!-- Submit Button -->
                <div class="w-full px-4 py-5 flex justify-center">
                    <button @click="handleSubmit"
                        class="flex min-w-[84px] cursor-pointer items-center justify-center overflow-hidden rounded-xl h-10 px-4 bg-[#5068f1] text-[#f8f9fc] text-sm font-bold leading-normal">
                        <span class="truncate">Send</span>
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { ref } from 'vue';
import VueDatePicker from '@vuepic/vue-datepicker';
import '@vuepic/vue-datepicker/dist/main.css';

const form = ref({
    cleaningType: '',
    date: '',
    time: '',
    fullName: '',
    phone: '',
    email: ''
});

const handleSubmit = () => {
    // Log the form data to console
    console.log('Form Data:', form.value);

    // Show alert message
    alert('Your information was sent successfully!');

    // Clear the form fields
    form.value = {
        cleaningType: '',
        date: '',
        time: '',
        fullName: '',
        phone: '',
        email: ''
    };
};
</script>