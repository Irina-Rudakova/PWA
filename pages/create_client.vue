<script setup lang="ts">

</script>

<template>
    <div class="my-0 w-full block">
        <section class="flex-col mb-6">
            <div class="flex items-center justify-center mb-8">
                <UIcon name="i-lucide-arrow-left" class="size-4 py-2.5 px-1.5 mr-auto " />
                <span class="text-Slate-800 text-lg font-medium leading-7 mr-auto">Новый клиент</span>
            </div>

            <div class="justify-start text-slate-800 text-xl font-bold leading-7">+ 7 (999) 123-45-67</div>
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
