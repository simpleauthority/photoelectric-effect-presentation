<script setup>
import { onMounted } from 'vue'

// Reveal dependencies
import Reveal from "reveal.js"
import Highlight from "reveal.js/plugin/highlight/highlight.js"
import { KaTeX } from "reveal.js/plugin/math/math.js"

// Reveal styles
import "reveal.js/dist/reveal.css"
import "reveal.js/dist/theme/blood.css"
import "reveal.js/plugin/highlight/monokai.css";

onMounted(() => {
  Reveal.initialize({
      center: false,
      width: 1280, // use 16:9 aspect ratio vs default 4:3
      height: 720,
      plugins: [Highlight, KaTeX]
  })
})
</script>

<template>
    <div class="reveal">
        <div class="slides">
            <slot></slot>
        </div>
    </div>
</template>

