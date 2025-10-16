<script setup lang="ts">

</script>

<template>
    <div class="my-0 w-full block">
        <section class="flex-col mb-8">
            <div class="flex items-center justify-center mb-8">
                <UIcon name="i-lucide-arrow-left" class="size-4 py-2.5 px-1.5 mr-auto" />
                <span class="text-Slate-800 text-lg font-medium leading-7 mr-auto">Сканировать
                    товар</span>
            </div>

            <div class="flex gap-2 justify-between">
                <UInput color="neutral" size="xl" placeholder="Поиск по штрих-коду" variant="soft" class="w-full"
                    trailing-icon="i-lucide-search" />
            </div>
        </section>

        <div class=" bg-slate-500 rounded-2xl h-[510px] p-6 flex-col">
            <UIcon name="i-lucide-flashlight" class="size-6  bg-white flex justify-end ml-auto mb-[164px]" />
            <section class="wrap">
                <div class="h-20 bg-white rounded-lg mb-2 items-center flex justify-center">
                    <hr class="w-full border-[#FB2C36]">
                </div>
                <span class="text-white text-center justify-center flex text-xs font-medium">Поместите штрих-код в
                    рамку,<br />
                    чтобы найти его в каталоге</span>
            </section>

        </div>

        <nav class="flex w-full grow gap-[27px] h-11 items-center justify-center fixed bottom-14 left-0 right-0">
            <UButton variant="link" color="secondary"
                class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <UIcon name="i-lucide-house" class="py-2.5 px-1.5 mr-auto w-full size-6" />
                <span>Главная</span>
            </UButton>
            <UButton variant="link" color="neutral" class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <UIcon name="i-lucide-text-search" class="py-2.5 px-1.5 mr-auto w-full size-6" />
                <span>Каталог</span>
            </UButton>
            <UButton variant="link" color="neutral" class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
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
text-secondary text-xs font-semibold leading-none