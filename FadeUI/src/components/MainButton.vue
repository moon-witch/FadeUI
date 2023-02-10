<script setup lang="ts">
const props = defineProps({
    content: String
})
</script>

<template>
    <button>
        {{ props.content }}
    </button>
</template>