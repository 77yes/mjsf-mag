<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <h1>Єгоров Сергій Юрійович</h1>
  <div class="card">
    <p>Інженерія програмного забезпечення</p>
    <p>2 курс</p>
    <p>група 8.1212-з</p>
  
    <button type="button" @click="count++">count is {{ count }}</button>
   
  </div>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
