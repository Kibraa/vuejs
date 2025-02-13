<template>
    <button :id="data.id" :type="data.type" :class="data.class">

    </button>
</template>

<script setup lang="ts">

interface ButtonComponentProperties{
  data: {
    id: string;
    type?: 'button' | 'submit' | 'reset';
    class?: string;
  }
}
defineProps<ButtonComponentProperties>();

</script>