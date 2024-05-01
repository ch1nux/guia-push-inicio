<script setup lang="ts">
import { useNav } from "@slidev/client"

const { go } = useNav()

const props = defineProps({
  slide: {
    type: Number,
    default: 0
  }
})
</script>

<template>
  <div 
    border="1 rounded-lg #E03DC1 hover:#8247E5" 
    h="10"
    p="x4 y2" 
    cursor="hover:pointer" 
    @click="go(props.slide)"
  >
    <slot />
  </div>
</template>
