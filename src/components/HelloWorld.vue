<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)

</script>

<template>
  <h1 class="text-3xl font-bold underline">Hola mundito</h1>
</template>

