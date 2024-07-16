<script setup lang="ts">
import { onMounted, reactive } from 'vue'

const screen = reactive({
  width: 0,
  height: 0,
  pixelRatio: 0,
  innerWidth: 0,
  innerHeight: 0,
})

onMounted(() => {
  screen.pixelRatio = window.devicePixelRatio
  screen.width = window.screen.width * screen.pixelRatio
  screen.height = window.screen.height * screen.pixelRatio
  screen.innerWidth = window.innerWidth
  screen.innerHeight = window.innerHeight
})
</script>

<template>
  <div>
    <h1>Screen</h1>

    <div>
      {{ screen.width }}
      x
      {{ screen.height }}
    </div>

    <h1>Browser</h1>

    <div>
      {{ screen.innerWidth }}
      x
      {{ screen.innerHeight }}
    </div>
  </div>
</template>
