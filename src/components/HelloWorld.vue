<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>



  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit this 
      <code>components/HelloWorld.vue</code> to test the website
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>

  <p>
    Install
    <a href="
    https://github.com/vuejs/vite-plugin-vue2-jsx" target="_blank"
      >Volar</a
    >, the official Vue + Vite starter
  </p>
  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit this 
      <code>components/HelloWorld.vue</code> to test the website
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/vuejs/language-tools" target="_blank">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
.read-the-docs:hover {
  color: #000;
}
.card {
  border: 1px solid #ccc;
  border-radius: 4px;
  padding: 20px;
  margin-top: 20px;
}

.card p {
  margin: 0;
}
</style>