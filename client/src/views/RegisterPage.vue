
<script setup lang="ts">
    import RegisterForm from '../components/RegisterForm.vue';
</script>

<template>
    <div class="h-screen w-full flex flex-col gap-3 justify-center items-center font-semibold bg-black">

        <div class="flex flex-col gap-5">

            <div class="flex items-center">
                <img src="/img/hashvault_logo.png" alt="Encyptify Logo" width="80" height="80">
                <h1 class="text-white text-5xl">HashVault</h1>
            </div>
        </div>

        <RegisterForm />
        
    </div>
</template>


<style>
    .background-image {
        background-image: url('/img/encryptify_bg.jpg');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;        
    }
</style>
