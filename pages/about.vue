<script setup lang="ts">
const items = ref(['Ярославль', 'Нижний Новгород', 'Москва', 'Александров', 'Владимир', 'Вологда', 'Иваново', 'Кинешма', 'Ковров', 'Кострома', 'Муром', 'Переславль-Залесский', 'Рыбинск', 'Рязань', 'Тверь', 'Тула', 'Углич', 'Череповец'])
</script>
<template>
    <div class="my-0 w-full block">
        <section class="flex flex-col items-center:first-child">
            <span class="flex text-[#1D293D] text-xl font-bold leading-7 mb-8">Заполните данные</span>
            <div class="flex flex-col gap-4 w-full">
                <UInput color="neutral" size="xl" placeholder="Имя" />
                <UInput color="neutral" size="xl" placeholder="Фамилия" />
                <UInputMenu color="neutral" size="xl" placeholder="Выберите филиал" :items="items" />
            </div>
        </section>

        <div class="flex mt-4">
            <UButton label="Продолжить" color="secondary" size="xl" class="justify-center w-full" />
        </div>
    </div>
</template>