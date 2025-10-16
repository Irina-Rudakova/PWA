<script setup lang="ts">
</script>

<template>
    <div class="my-0 w-full block">
        <section class="flex-col">
            <div class="flex items-center justify-center mb-8">
                <UIcon name="i-lucide-arrow-left" class="size-4 py-2.5 px-1.5 mr-auto" />
                <span class="text-Slate-800 text-lg font-medium leading-7 mr-auto">Каталог</span>
            </div>

            <div class="flex gap-2 justify-between mb-6">
                <UInput icon="i-lucide-search" color="neutral" size="xl" placeholder="Поиск товаров" variant="soft"
                    class="w-full" />
                <UButton icon="i-lucide-scan-barcode" color="secondary" variant="outline" size="xl"
                    class="w-12 justify-center py-2 px-3" />
            </div>

            <div class="flex-col mb-4">
                <h4 class="justify-start text-slate-800 text-base font-medium leading-normal mb-0.5">Аккумуляторные
                    шуруповерты
                </h4>
                <p class="justify-start text-slate-400 text-xs font-normal leading-none">120 товаров</p>
            </div>
            <div>
                <UButton icon="i-lucide-sliders-vertical" color="neutral" variant="outline" size="xl"
                    class="justify-center w-full">Фильтры</UButton>
            </div>
        </section>

        <UContainer>
            <Placeholder class="h-32" />
        </UContainer>


        <nav class="flex w-full grow gap-[27px] h-11 items-center justify-center fixed bottom-14 left-0 right-0">
            <UButton variant="link" color="neutral" class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <UIcon name="i-lucide-house" class="py-2.5 px-1.5 mr-auto w-full size-6" />
                <span>Главная</span>
            </UButton>
            <UButton variant="link" color="secondary"
                class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
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