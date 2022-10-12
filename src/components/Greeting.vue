<script setup></script>

<template>
  <div>
    <button @click="$emit('add', Math.random() * 10)">random</button>
  </div>
</template>

<style scoped></style>
