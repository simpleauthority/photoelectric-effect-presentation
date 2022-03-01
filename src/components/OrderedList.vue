<script setup>
defineProps({
    'items': {
        type: Array,
        required: true
    },
    'highlighted': {
        type: Number,
        required: false,
        default: undefined
    },
    'stricken': {
        type: Array,
        required: false,
        default: undefined
    }
})
</script>

<template>
    <ol>
        <li v-for="(item, idx) in items" :key="`li-${idx}`">
            <span :class="highlighted === idx ? 'bg-yellow-300 text-slate-700' : 
                stricken && stricken.includes(idx) ? 'strikethrough' : ''">
                {{ item }}
            </span>
        </li>
    </ol>
</template>