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
            <h3 data-id="head">Electron energy levels?<br />Planck's constant?</h3>
            <div data-id="margin" class="mt-5"></div>
            <div data-id="img2list" class="flex justify-center items-center">
                <img src="@/images/cat-what.gif" alt="Confused cat" />
            </div>
        </section>
        <section data-auto-animate>
            <h3 data-id="head">Electron energy levels?<br />Planck's constant?</h3>
            <div data-id="margin" class="mt-20"></div>
            <OrderedList
                data-id="img2list"
                :items="bigIdeas"
                :highlighted="2"
                :stricken="[0, 1]"
            />
        </section>
    </section>
</template>

<style scoped>
img {
     height: 400px;
}
</style>