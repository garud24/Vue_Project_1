<script setup>
function saymyName(num){
  return num + 'Shivani'
}
</script>

<template>
  <h1 class="red">Hello World</h1>

  <div>  </div>
  <!-- <div v-if="false">My name is {{ saymyName(10) }} </div> -->
   <h1 v-if="false"> My name is {{ saymyName(10) }}</h1>
   <h1 v-else="true">My name is {{ 'Himanshu'.toLocaleUpperCase() }}</h1>
</template>

<style>
.red{
  color:red
}
</style>

