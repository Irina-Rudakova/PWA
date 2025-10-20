<script setup>
const asMobile = ref(true)
</script>

<template>
    <UApp>
        <div class="flex flex-col bg-white max-w-[1200px] min-h-lvh b mx-auto items-center ring-1 px-[15px] pt-6"
            :class="{ 'w-[374px]': asMobile }">
            <NuxtPage />
        </div>
    </UApp>
</template>

<style></style>