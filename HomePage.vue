<template>
    <main>
        <ButtonComponent :data="{ id: 'submit', type: 'submit', class: 'bg-sky-300 p-2 cursor-pointer' }" />
    </main>
</template>

<script setup lang="ts">
import ButtonComponent from '../components/ButtonComponent.vue';
</script>