<script setup>
import { onMounted } from 'vue'

// Reveal dependencies
import Reveal from "reveal.js"
import Markdown from "reveal.js/plugin/markdown/markdown.js"
import Highlight from "reveal.js/plugin/highlight/highlight.js"
import { KaTeX } from "reveal.js/plugin/math/math.js"

// Reveal styles
import "reveal.js/dist/reveal.css"
import "reveal.js/dist/theme/black.css"
import "reveal.js/plugin/highlight/monokai.css";

onMounted(() => {
  Reveal.initialize({
      plugins: [Markdown, Highlight, KaTeX]
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

