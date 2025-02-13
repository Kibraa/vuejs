<template>
    <article>
        <label :for="data.id"></label>
        <input :type="data.type ? data.type : 'text'" :placeholder="data.placeholder" :class="data.class"/>
    </article>
</template>

<script setup lang="ts">

interface FieldsComponentProperties{
    data:{
        id: string;
        email: string;
        placeholder: string;
        type?: string;
        class?: string;
    }
}
defineProps<FieldsComponentProperties>();

</script>