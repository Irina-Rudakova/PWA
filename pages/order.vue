<script setup lang="ts">
import type { TabsItem } from '@nuxt/ui'

const items = ref<TabsItem[]>([
    {
        label: 'Номер заказа',
        content: 'Заказ'
    },
    {
        label: 'Номер телефона',
        content: 'Телефон'
    }
])
</script>

<template>
    <div class="my-0 w-full block">
        <section class="flex-col">
            <div class="flex items-center justify-center mb-8">
                <UIcon name="i-lucide-arrow-left" class="size-4 py-2.5 px-1.5 mr-auto" />
                <span class="text-Slate-800 text-lg font-medium leading-7 mr-auto">Выдача заказа</span>
            </div>

            <!-- <div
                class="w-full h-10 text-sm font-medium leading-tight rounded-md inline-flex bg-elevated mb-6 justify-center items-center">
                <UButton color="neutral" variant="solid" label="Номер заказа"
                    class="w-full h-8 gap-1.5 justify-center items-center flex-1 px-2.5 py-1.5" />
                <UButton color="neutral" variant="soft" label="Номер телефона"
                    class="w-full h-8 gap-1.5 justify-center items-center flex-1 px-2.5 py-1.5" />
            </div> 
            <div class="flex gap-2 justify-between">
                <UInput color="neutral" size="xl" placeholder="Заказ" variant="soft" class="w-full"
                    trailing-icon="i-lucide-search" />

                placeholder="Телефон"
             </div> -->

            <UTabs :items="items" class="w-full justify-center items-center gap-6" color="neutral">
                <template #content="{ item }">
                    <div class="flex gap-2 justify-between">
                        <UInput size="xl" :placeholder="item.content" variant="soft"
                            class="w-full text-base font-normal justify-center items-center"
                            trailing-icon="i-lucide-search">
                        </UInput>
                    </div>
                </template>
            </UTabs>


        </section>

        <nav class="flex w-full grow gap-[27px] h-11 items-center justify-center fixed bottom-14 left-0 right-0">
            <UButton variant="link" color="neutral" class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
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
            <UButton variant="link" color="secondary"
                class="flex-col w-auto h-6 p-0 text-xs font-semibold leading-none">
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