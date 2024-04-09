<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <template v-for="item of 10">
      <div :key="item">{{ item }}</div>
    </template>
    <template v-for="i of a">
      <div :key="i">{{ i }}</div>
    </template>
  </div>
</template>

<script setup lang="ts">

const a=[1,2,3,4,5,6,7,8,9]

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
