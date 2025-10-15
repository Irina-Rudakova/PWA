<script setup lang="ts">
</script>

<template>
    <div class="my-0 w-full block">
        <section class="flex-col mb-4">
            <div class="flex items-center justify-center mb-8">
                <UIcon name="i-lucide-arrow-left" class="size-4 py-2.5 px-1.5 mr-auto" />
                <span class="text-Slate-800 text-lg font-medium leading-7 mr-auto">Каталог</span>
            </div>

            <div class="flex gap-2 justify-between mb-6">
                <UInput icon="i-lucide-search" color="neutral" size="xl" placeholder="Поиск товаров" variant="soft"
                    class="w-full" />
                <UButton icon="i-lucide-scan-barcode" color="secondary" variant="outline" size="xl" />
            </div>

            <UButton icon="i-lucide-sparkles size-6" label="ИИ-подбор товаров" bg="neutral" variant="soft"
                color="secondary" size="xl" class="justify-center w-full text-base font-medium" />
        </section>

        <div class="mb-[22px] flex-col wrap">
            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Инструмент</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Все для сада и огорода</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span class="text-start">Водоснабжение, сантехника и отопление</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Сварочное оборудование</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Станки</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Строительная техника</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Климатическое оборудование</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Уборка и клининг</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Электрика и свет</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Автотовары</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>

            <UButton color="neutral" variant="ghost" size="xl" class="justify-between w-full ">
                <span>Средства индивидуальной защиты</span>
                <UIcon name="i-lucide-chevron-right" class="size-6" />
            </UButton>


            <!-- border-b-1 solid border-black rounded-none -->
        </div>

        <!-- <UNavigationMenu :items="items" class="w-full justify-center" color="secondary" variant="link"
            orientation="horizontal" /> -->
        <nav class="flex w-full grow gap-[27px] h-11 items-center justify-center">
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