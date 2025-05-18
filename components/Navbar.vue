<script setup>
import { AlignJustify } from 'lucide-vue-next';
import Divider from './Divider.vue';
</script>

<template>
    <nav class="w-[15vw] p-6 h-screen bg-black flex flex-col gap-4">
        <div class="flex items-center gap-3 font-bold">
            <AlignJustify color="#fff" class="w-6 h-6" stroke-width="3" />
            <h1 class="text-white">Dashboard Shop</h1>
        </div>
        <Divider />
    </nav>
</template>