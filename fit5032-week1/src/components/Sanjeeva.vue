<template>
  <div class="sanjeeva">
    <h2>{{ greeting }}</h2>
    <p>
      My name is <strong>{{ name }}</strong>
    </p>
    <p>{{ description }}</p>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const name = ref('Sanjeeva Reddy')
const greeting = ref('Hello!')
const description = ref('Welcome to my Vue.js application!')
</script>

<style scoped>
.sanjeeva {
  padding: 1.5rem;
  border: 1px solid #e0e0e0;
  border-radius: 5px;
  text-align: center;
  margin: 1rem 0;
  background-color: #f9f9f9;
}

.sanjeeva h2 {
  margin-bottom: 1rem;
  font-size: 1.8rem;
  color: #333;
}

.sanjeeva p {
  margin: 0.5rem 0;
  font-size: 1rem;
  color: #666;
}

.sanjeeva strong {
  color: #000;
  font-weight: bold;
}
</style>