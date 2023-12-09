<script setup>
import { debounceRef } from '../utils/debounce'
const text = debounceRef('')
console.log(text)
</script>

<template>
  <input type="text" v-model="text" />
  <p class="result">{{ text }}</p>
</template>
