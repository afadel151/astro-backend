<script setup lang="ts">
import StarsBackground from '~/components/ui/bg-stars/StarsBackground.vue';
import Header from '~/components/hero/Header.vue';

</script>


<template>
    <div
        class="relative   flex flex-col h-[2000px] ">
        <StarsBackground :factor="0.05" :speed="50" star-color="#fff" class="absolute inset-0 -z-10"/>
        <Header class="sticky top-0 right-0 z-50 w-full" />
    </div>
</template>
