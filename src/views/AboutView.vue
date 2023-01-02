<script setup>
import {ref, onMounted} from 'vue'

let messages = ref({})

onMounted(() => {
  document.addEventListener("deviceready", onDeviceReady, false)
  function onDeviceReady() {
    alert(navigator.camera)
  }
})
</script>

<template>
  <div class="about">
    {{ messages }}
  </div>
</template>

<style>
</style>
