<script setup>
console.log('window.jinlin', window.jinlin.pika)
const pika = window.jinlin.pika;
</script>

<template>
  <div>
    home
    <div>我的精灵是：{{ pika }}</div>
    <!-- <div>我的精灵是：{{ window.jinlin.pika }}</div> --> 
  </div>
</template>
