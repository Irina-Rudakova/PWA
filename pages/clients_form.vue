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


        <div class="h-[112px] w-full p-2.5 bg-amber-300">
            <img src="#" alt="штрихкод">
        </div>

        <section class="flex justify-start gap-2 mt-3">
            <UBadge size="sm" color="neutral" variant="soft"
                class="px-1.5 py-1 rounded-md inline-flex justify-center items-center gap-1">
                Закупка: 3 467 ₽
            </UBadge>
            <UBadge size="sm" color="secondary" variant="soft"
                class="px-1.5 py-1  rounded-md inline-flex justify-center items-center gap-1">
                Продажа: 5 591 ₽
            </UBadge>
            <UBadge icon="i-lucide-rocket" size="md" color="primary" variant="solid">Badge</UBadge>

        </section>

        <div class="flex flex-col">
            <div class="flex flex-col gap-3 ">
                <UFormField label="Имя, Фамилия" required size="xl">
                    <UInput placeholder="" class="w-full" color="neutral" />
                </UFormField>

                <UFormField label="E-mail" size="xl">
                    <UInput placeholder="" class="w-full" color="neutral" />
                </UFormField>

                <UFormField label="Дата рождения" size="xl">
                    <UInput placeholder="" class="w-full" color="neutral" />
                </UFormField>
            </div>

            <UButton label="Зарегистрировать" color="secondary" size="xl" class="justify-center w-full  mt-10" />
        </div>


        <nav class="flex w-full grow gap-[27px] h-11 items-center justify-center fixed bottom-14 left-0 right-0">
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
