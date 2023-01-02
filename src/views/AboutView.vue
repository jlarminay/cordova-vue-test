<script setup>
import {ref, onMounted} from 'vue'

let messages = ref({})

onMounted(() => {
  smsreader.getAllSMS()
    .then((sms)=>{
      messages.value = sms
    },
    (err)=>{
      alert(err)
    });
})
</script>

<template>
  <div class="about">
    {{ messages }}
  </div>
</template>

<style>
</style>
