<script setup lang="ts">
const items = ref(['Ярославль', 'Нижний Новгород', 'Москва', 'Александров', 'Владимир', 'Вологда', 'Иваново', 'Кинешма', 'Ковров', 'Кострома', 'Муром', 'Переславль-Залесский', 'Рыбинск', 'Рязань', 'Тверь', 'Тула', 'Углич', 'Череповец']);
const category = ref(['Пилы', 'Пилы',])
</script>


<template>
    <div class="my-0 w-full block">
        <section class="flex-col items-center mb-8">
            <!-- <div class="flex justify-between">
                <UButton color="neutral" variant="link" class="p-0">
                    <UIcon name="i-lucide-arrow-left"
                        class="size-2.5 py-2.5 p-1.5 mr-auto border-2 solid bg-[#314158]" />
                </UButton>
                <span class="text-Slate-800 text-lg font-medium leading-7 mr-auto flex items-center">ИИ-подбор
                    товаров</span>
            </div> -->

            <div class="flex items-center justify-center mb-8">
                <UIcon name="i-lucide-arrow-left" class="size-4 py-2.5 px-1.5 mr-auto" src="#" />
                <span class="text-Slate-800 text-lg font-medium leading-7 mr-auto">ИИ-подбор товаров</span>
            </div>

        </section>

        <div class="flex flex-col gap-3">
            <div class="flex flex-col gap-2 w-full">
                <h3 class="justify-start text-base font-medium leading-normal">Магазин</h3>
                <UInputMenu color="neutral" size="xl" placeholder="Выберите филиал" :items="items" />
            </div>

            <div class="flex flex-col gap-2 w-full">
                <h3 class="justify-start text-base font-medium leading-normal">Категория </h3>
                <UInputMenu color="neutral" size="xl" placeholder="Поиск категории" :items="category" />
            </div>

            <div class="flex mt-10">
                <UButton label="Продолжить" color="secondary" size="xl" class="justify-center w-full" />
            </div>
        </div>

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