<script setup>
import DropdownItem from './components/DropdownItem.vue';

</script>

<template>
    <div class="lg:w-auto lg:flex lg:justify-center lg:items-stretch lg:mt-0 w-80 min-h-[33rem] mt-12 shadow-[0_2.5rem_2rem_#00000030] relative bg-white rounded-3xl">
        <div class="lg:w-1/2 relative">
            <div class="lg:overflow-hidden lg:relative lg:flex lg:items-center h-full">
                <picture>
                    <source
                        srcset="./assets/images/illustration-woman-online-desktop.svg"
                        media="(min-width: 1024px)"
                    >
                    <img class="lg:-left-[4.25rem] lg:top-0 lg:relative lg:z-10 lg:w-auto lg:max-w-full lg:drop-shadow-none w-60 absolute -top-[6.75rem] left-11 mx-auto drop-shadow-[0_2rem_0_#aaaaff30]" src="./assets/images/illustration-woman-online-mobile.svg" alt="illustration">
                    
                </picture>
                
                <img class="hidden lg:block absolute -left-[17.9rem] top-2 scale-[2]" src="./assets/images/bg-pattern-desktop.svg" alt="background pattern">
            </div>
            <img src="./assets/images/illustration-box-desktop.svg" alt="illustration box" class="hidden lg:inline-block absolute left-0 z-10 top-[13.5rem] -translate-x-1/2">
        </div>

        <div class="lg:pr-16 lg:w-1/2">
            <h1 class="lg:mt-16 lg:text-left text-4xl font-bold text-dark-blue text-center mt-[8.5rem] mb-7">FAQ</h1>
            <DropdownItem>
                <template #header>How many team members can I invite? </template>
                You can invite up to 2 additional users on the Free plan. There is no  limit on team members for the Premium plan.
            </DropdownItem>
            <DropdownItem>
                <template #header>What is the maximum file upload size? </template>
                No more than 2GB. All files in your account must fit your allotted storage space.
            </DropdownItem>
            <DropdownItem>
                <template #header>How do I reset my password? </template>
                Click “Forgot password” from the login page or “Change password” from your profile page. A reset link will be emailed to you.template>
            </DropdownItem>
            <DropdownItem>
                <template #header>Can I cancel my subscription? </template>
            
                Yes! Send us a message and we’ll process your request no questions asked.
            </DropdownItem>
            <DropdownItem>
                <template #header>Do you provide additional support? </template>
                Chat and email support is available 24/7. Phone lines are open during normal business hours.
            </DropdownItem>
        </div>
    </div>
    <div class="text-xs fixed bottom-5 text-center w-full">
        Challenge by
        <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">
            Frontend Mentor
        </a>
        . Coded by
        <a href="#">Sofus</a>
        .
    </div>
</template>
