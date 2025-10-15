<script setup></script>
<template>
    <div class="my-auto w-full block justify-center">
        <section class="flex flex-col items-center">
            <span class=" text-[#1D293D] text-xl font-bold leading-7 justify-center mb-8">Авторизация</span>
            <div class="flex flex-col gap-4 w-full">
                <UInput color="neutral" size="xl" placeholder="Логин" />
                <UInput color="neutral" size="xl" placeholder="Пароль" />
            </div>
        </section>
        <div class="flex mt-4">
            <UButton label="Войти" color="secondary" size="xl" class="justify-center w-full" />
        </div>
    </div>
</template>