<template>
    <button @click="props.func()"></button>
</template>
<script setup lang="js">
    const props = defineProps({
        func: {
            Type: Function,
        }
    })
</script>