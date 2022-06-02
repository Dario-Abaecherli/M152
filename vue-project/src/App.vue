<template>
  <h1>Hello {{ name }}</h1>
  <input v-model="name" />
</template>

<script>
import { ref } from 'vue';

export default {
  name: 'App',
  setup() {
    const name = ref('');

    return {
      name
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
