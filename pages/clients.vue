<script setup lang="ts">

</script>

<template>
    <div class="my-0 w-full block">
        <section class="flex-col mb-6">
            <div class="flex items-center justify-center mb-8">
                <UIcon name="i-lucide-arrow-left" class="size-4 py-2.5 px-1.5 mr-auto " />
                <span class="text-Slate-800 text-lg font-medium leading-7 mr-auto">Клиенты</span>
            </div>

            <div class="flex gap-2 justify-between">
                <UInput color="neutral" size="xl" placeholder="Телефон" variant="soft" class="w-full"
                    trailing-icon="i-lucide-search" />
            </div>
        </section>


        <!-- Скрытая секция -->
        <section class="flex-col mb-[454px]">
            <h5 class="mb-6 text-slate-400 justify-center flex">Клиент не найден</h5>
            <UButton icon="i-lucide-user-plus" label="Зарегистрировать клиента" color="secondary" size="xl"
                class="justify-center w-full mb-4" />
        </section>



        <nav class="flex w-full grow gap-[27px] h-11 items-center justify-center">
            <UButton variant="link" color="neutral" class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <UIcon name="i-lucide-house" class="py-2.5 px-1.5 mr-auto w-full size-6" />
                <span>Главная</span>
            </UButton>
            <UButton variant="link" color="neutral" class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <UIcon name="i-lucide-text-search" class="py-2.5 px-1.5 mr-auto w-full size-6" />
                <span>Каталог</span>
            </UButton>
            <UButton variant="link" color="secondary"
                class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <UIcon name="i-lucide-users" class="py-2.5 px-1.5 mr-auto w-full size-6" />
                <span>Клиенты</span>
            </UButton>
            <UButton variant="link" color="neutral" class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <UIcon name="i-lucide-package" class="py-2.5 px-1.5 mr-auto w-full size-6" />
                <span>Заказы</span>
            </UButton>
            <UButton variant="link" color="neutral" class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <UIcon name="i-lucide-user-round" class="py-2.5 px-1.5 mr-auto w-full size-6" />
                <span>Профиль</span>
            </UButton>
        </nav>
    </div>

</template>
