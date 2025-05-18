<script setup>
import { AlignJustify, BadgeDollarSign, ShoppingBasket, ChartNoAxesGantt } from 'lucide-vue-next';
import Divider from '@/components/ui/Divider.vue';
</script>

<template>
    <nav class="w-[15vw] max-md:w-[50vw] p-6 h-screen bg-green-500 flex flex-col gap-6">
        <div class="flex items-center gap-3 font-bold">
            <AlignJustify color="#fff" class="w-6 h-6" stroke-width="3" />
            <h1 class="text-white">Dashboard Shop</h1>
        </div>
        <Divider />
        <NuxtLink to="/sales">
            <div class="flex items-center gap-3">
                <BadgeDollarSign color="#fff" class="w-6 h-6" stroke-width="3" />
                <h2 class="text-white font-bold">
                    Ventas
                </h2>
            </div>
        </NuxtLink>
        <NuxtLink to="/products">
            <div class="flex items-center gap-3">
                <ShoppingBasket color="#fff" class="w-6 h-6" stroke-width="3" />
                <h2 class="text-white font-bold">
                    Productos
                </h2>
            </div>
        </NuxtLink>
        <NuxtLink to="/categories">
            <div class="flex items-center gap-3">
                <ChartNoAxesGantt color="#fff" class="w-6 h-6" stroke-width="3" />
                <h2 class="text-white font-bold">
                    Categorías
                </h2>
            </div>
        </NuxtLink>
    </nav>
</template>