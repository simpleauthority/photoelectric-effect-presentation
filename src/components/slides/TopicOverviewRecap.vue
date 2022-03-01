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
            <h4>That's the end...for now!</h4>
            <div class="mt-20"></div>
            <div class="grid grid-cols-2 gap-6">
                <div>    
                    <img src="@/images/thats-all-folks.jpg" alt="Confused cat" />
                </div>
                <OrderedList 
                    :items="bigIdeas"
                    :stricken="[0, 1, 2]"
                />
            </div>
        </section>
    </section>
</template>