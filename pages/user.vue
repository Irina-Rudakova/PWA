<script setup lang="ts">
// import type { NavigationMenuItem } from '@nuxt/ui'

// const items: NavigationMenuItem[] = [
//     {
//         label: 'Главная',
//         icon: 'i-lucide-house',
//         active: true,
//         button: 'wrap'
//     },
//     {
//         label: 'Каталог',
//         icon: 'i-lucide-text-search',

//     },
//     {
//         label: 'Клиенты',
//         icon: 'i-lucide-users',

//     },
//     {
//         label: 'Заказы',
//         icon: 'i-lucide-package',
//     },
//     {
//         label: 'Профиль',
//         icon: 'i-lucide-circle-user-round',
//     }
// ]
</script>

<template>
    <div class="my-0 w-full block">
        <section class="flex-col mb-8">
            <div class="flex items-center gap-4 pb-8">
                <UChip inset>
                    <UAvatar icon="i-lucide-user-round" src="" size="2xl" />
                </UChip>
                <div class="grid gap-2 pl-3">
                    <span class="text-slate-800 text-sm font-semibold leading-5">Константин Константинопольский</span>
                    <p class="text-slate-400 text-sm font-normal leading-5">Нижний Новгород-1</p>
                </div>
            </div>

            <div class="flex gap-2 justify-between">
                <UInput icon="i-lucide-search" color="neutral" size="xl" placeholder="Поиск товаров" variant="soft"
                    class="w-full" />
                <UButton icon="i-lucide-scan-barcode" color="secondary" variant="outline" size="xl" />
            </div>
        </section>
        <section class="flex-col-2 mb-[60px]">
            <div class="flex gap-4 pb-4 h-auto">
                <UButton color="neutral" variant="outline"
                    class="flex flex-col w-[164px] text-Slate-800 text-base font-medium leading-normal p-3 items-start">
                    <div class="flex">
                        <UBadge bg="neutral" variant="soft" icon="i-lucide-sparkles w-full" color="secondary"
                            class="size-12 p-3 items-center"></UBadge>
                    </div>
                    <div>
                        <h3 class="">Подбор товаров</h3>
                    </div>

                </UButton>

                <UButton color="neutral" variant="outline"
                    class="flex flex-col w-[164px] text-Slate-800 text-base font-medium leading-normal p-3 items-start">
                    <div class="flex">
                        <UBadge bg="neutral" variant="soft" icon="i-lucide-shopping-bag w-full" color="secondary"
                            class="size-12 p-3 items-center"></UBadge>
                    </div>
                    <div>
                        <h3 class="">Выдача заказа</h3>
                    </div>
                </UButton>
            </div>

            <UButton color="neutral" variant="outline"
                class=" flex w-full h-[72px] text-Slate-800 text-base font-medium leading-normal p-3 gap-3 justify-start">
                <div class="flex">
                    <UBadge bg="neutral" variant="soft" icon="i-lucide-users w-full" color="secondary"
                        class="size-12 p-3 items-center"></UBadge>
                </div>
                <div>
                    <h3 class="">Поиск/регистрация клиента</h3>
                </div>
            </UButton>

        </section>
        <div class="mb-[166px]">
            <UButton icon="i-lucide-shopping-cart" label="Корзина и оформление" color="secondary" size="xl"
                class="justify-center w-full mb-4" />
            <UButton icon="i-lucide-scan-barcode" label="Сканировать товар" color="secondary" variant="outline"
                size="xl" class="justify-center w-full" />
        </div>
        <!-- <UNavigationMenu :items="items" class="w-full justify-center" color="secondary" variant="link"
            orientation="horizontal" /> -->
        <nav class="flex w-full grow gap-[27px] h-11 j">
            <UButton icon="i-lucide-house w-full size-6" label="" variant="link" color="secondary"
                class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <span>Главная</span>
            </UButton>
            <UButton icon="i-lucide-text-search w-full size-6" label="" variant="link" color="neutral"
                class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <span>Каталог</span>
            </UButton>
            <UButton icon="i-lucide-users w-full size-6" label="" variant="link" color="neutral"
                class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <span>Клиенты</span>
            </UButton>
            <UButton icon="i-lucide-package w-full size-6" label="" variant="link" color="neutral"
                class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <span>Заказы</span>
            </UButton>
            <UButton icon="i-lucide-user-round w-full size-6" label="" variant="link" color="neutral"
                class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
                <span>Профиль</span>
            </UButton>
        </nav>
    </div>

</template>
text-secondary text-xs font-semibold leading-none