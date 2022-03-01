<script setup>
import OrderedList from '../OrderedList.vue';

defineProps({
    'bigIdeas': {
        type: Array,
        required: true
    }
})
</script>

<template>
    <section>
        <section data-auto-animate>
            <h3>So, what's the big idea?</h3>
            <h4>Three things:</h4>
            <div class="mt-20"></div>
            <OrderedList 
                :items="bigIdeas"
            />
        </section>
        <section data-auto-animate>
            <h3>So, what's the big idea?</h3>
            <h4>Three things:</h4>
            <div class="mt-20"></div>
            <OrderedList 
                :items="bigIdeas"
                :highlighted="0"
            />
        </section>
    </section>
</template>