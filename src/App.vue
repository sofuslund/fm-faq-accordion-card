<script setup>
import HelloWorld from './components/HelloWorld.vue';
import TheWelcome from './components/TheWelcome.vue';
</script>

<template>
    How many team members can I invite? You can invite up to 2 additional users
    on the Free plan. There is no limit on team members for the Premium plan.
    What is the maximum file upload size? No more than 2GB. All files in your
    account must fit your allotted storage space. How do I reset my password?
    Click “Forgot password” from the login page or “Change password” from your
    profile page. A reset link will be emailed to you. Can I cancel my
    subscription? Yes! Send us a message and we’ll process your request no
    questions asked. Do you provide additional support? Chat and email support
    is available 24/7. Phone lines are open during normal business hours.

    <div class="attribution">
        Challenge by
        <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">
            Frontend Mentor
        </a>
        . Coded by
        <a href="#">Your Name Here</a>
        .
    </div>
</template>

<style>
@import './assets/base.css';

#app {
    max-width: 1280px;
    margin: 0 auto;
    padding: 2rem;

    font-weight: normal;
}

header {
    line-height: 1.5;
}

.logo {
    display: block;
    margin: 0 auto 2rem;
}

a,
.green {
    text-decoration: none;
    color: hsla(160, 100%, 37%, 1);
    transition: 0.4s;
}

@media (hover: hover) {
    a:hover {
        background-color: hsla(160, 100%, 37%, 0.2);
    }
}

@media (min-width: 1024px) {
    body {
        display: flex;
        place-items: center;
    }

    #app {
        display: grid;
        grid-template-columns: 1fr 1fr;
        padding: 0 2rem;
    }

    header {
        display: flex;
        place-items: center;
        padding-right: calc(var(--section-gap) / 2);
    }

    header .wrapper {
        display: flex;
        place-items: flex-start;
        flex-wrap: wrap;
    }

    .logo {
        margin: 0 2rem 0 0;
    }
}
</style>
