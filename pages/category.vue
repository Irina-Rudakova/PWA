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
                <h1 class="justify-start text-slate-800 text-base font-medium leading-normal mb-0.5">Аккумуляторные
                    шуруповерты
                </h1>
                <p class="justify-start text-slate-400 text-xs font-normal leading-none">120 товаров</p>
            </div>
            <div>
                <UButton icon="i-lucide-sliders-vertical" color="neutral" variant="outline" size="xl"
                    class="justify-center w-full">Фильтры</UButton>
            </div>
        </section>

        <article class="flex w-full gap-4 mt-6">
            <div class="outline-amber-400 outline-1 size-[74px] items-center justify-center">
                <img src="#" alt="Фото дрели" class="size-[74px] ">

            </div>

            <article class="">
                <div class="inline-flex gap-2.5 items-center mb-2">
                    <p class="justify-start text-slate-400 text-xs font-normal leading-none p-0">X1048041302532</p>
                    <UIcon name="i-lucide-copy" class="size-4 justify-center items-center py-px bg-neutral-400" />
                </div>

                <h2 class="justify-start text-slate-800 text-sm font-medium leading-tight mb-3">Аккумуляторная
                    дрель-шуруповерт Вихрь ДА-18Л-2К 72/14/9</h2>

                <div class="inline-flex items-center gap-3">
                    <p class="text-xl font-bold leading-7 text-slate-800">5 591 ₽</p>
                    <UButton color="warning" variant="solid" active-color="primary" active-variant="solid">
                        3.5 (196)
                    </UButton>
                </div>

                <div class="grid justify-start gap-1 mt-3">
                    <div class="inline-flex text-xs font-normal leading-none gap-0.5">
                        <h4 class="text-slate-400">Остаток:</h4>
                        <p>12 шт</p>
                    </div>

                    <div class="inline-flex text-xs font-normal leading-none gap-0.5">
                        <h4 class="text-slate-400">Доставка:</h4>
                        <p>15 октября</p>
                    </div>
                </div>

                <section class="grid grid-rows-2 grid-flow-col justify-start gap-2 mt-3">
                    <UBadge size="sm" color="neutral" variant="soft"
                        class="px-1.5 py-1 rounded-md inline-flex justify-center items-center gap-1">
                        Закупка: 3 467 ₽
                    </UBadge>
                    <UBadge size="sm" color="secondary" variant="soft"
                        class="px-1.5 py-1  rounded-md inline-flex justify-center items-center gap-1">
                        Продажа: 5 591 ₽
                    </UBadge>
                    <UBadge size="sm" color="primary" variant="soft"
                        class="px-1.5 py-1  rounded-md inline-flex justify-center items-center gap-1">
                        Прибыль: 2 124 ₽
                    </UBadge>
                    <UBadge size="sm" color="primary" variant="outline"
                        class="px-1.5 py-1 rounded-md inline-flex justify-center items-center gap-1">
                        Маржа: 38%
                    </UBadge>
                </section>

                <div class="inline-flex gap-3 items-center w-full mt-3">
                    <UButton label="В корзину" color="secondary" variant="solid" size="lg"
                        class="justify-center w-[140px]" />

                    <UButton icon="lucide:ellipsis-vertical" color="neutral" variant="outline"
                        class="justify-center w-11" />
                </div>

            </article>
        </article>

        <article class="flex w-full gap-4 mt-6">
            <div class="outline-amber-400 outline-1 size-[74px] items-center justify-center">
                <img src="#" alt="Фото дрели" class="size-[74px] ">

            </div>

            <article class="">
                <div class="inline-flex gap-2.5 items-center mb-2">
                    <p class="justify-start text-slate-400 text-xs font-normal leading-none p-0">X1048041302532</p>
                    <UIcon name="i-lucide-copy" class="size-4 justify-center items-center py-px bg-neutral-400" />
                </div>

                <h2 class="justify-start text-slate-800 text-sm font-medium leading-tight mb-3">Аккумуляторная
                    дрель-шуруповерт Вихрь ДА-18Л-2К 72/14/9</h2>

                <div class="inline-flex items-center gap-3">
                    <p class="text-xl font-bold leading-7 text-slate-800">5 591 ₽</p>
                    <UButton color="warning" variant="solid" active-color="primary" active-variant="solid">
                        3.5 (196)
                    </UButton>
                </div>

                <div class="grid justify-start gap-1 mt-3">
                    <div class="inline-flex text-xs font-normal leading-none gap-0.5">
                        <h4 class="text-slate-400">Остаток:</h4>
                        <p>12 шт</p>
                    </div>

                    <div class="inline-flex text-xs font-normal leading-none gap-0.5">
                        <h4 class="text-slate-400">Доставка:</h4>
                        <p>15 октября</p>
                    </div>
                </div>

                <section class="grid grid-rows-2 grid-flow-col justify-start gap-2 mt-3">
                    <UBadge size="sm" color="neutral" variant="soft"
                        class="px-1.5 py-1 rounded-md inline-flex justify-center items-center gap-1">
                        Закупка: 3 467 ₽
                    </UBadge>
                    <UBadge size="sm" color="secondary" variant="soft"
                        class="px-1.5 py-1  rounded-md inline-flex justify-center items-center gap-1">
                        Продажа: 5 591 ₽
                    </UBadge>
                    <UBadge size="sm" color="primary" variant="soft"
                        class="px-1.5 py-1  rounded-md inline-flex justify-center items-center gap-1">
                        Прибыль: 2 124 ₽
                    </UBadge>
                    <UBadge size="sm" color="primary" variant="outline"
                        class="px-1.5 py-1 rounded-md inline-flex justify-center items-center gap-1">
                        Маржа: 38%
                    </UBadge>
                </section>

                <div class="inline-flex gap-3 items-center w-full mt-3">
                    <UButton label="В корзину" color="secondary" variant="solid" size="lg"
                        class="justify-center w-[140px]" />

                    <UButton icon="lucide:ellipsis-vertical" color="neutral" variant="outline"
                        class="justify-center w-11" />
                </div>

            </article>
        </article>


        <nav class=" flex w-full grow gap-[27px] h-11 items-center justify-center fixed bottom-14 left-0 right-0">
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