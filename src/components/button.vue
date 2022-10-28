<script setup>
defineProps({
  text: {
    type: String,
    required: true
  },
  link: {
    type: String,
    required: false
  }
})
</script>

<template>
<a class="button" :href=link>{{text}}</a>
</template>