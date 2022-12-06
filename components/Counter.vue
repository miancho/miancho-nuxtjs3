<template>
  <div>
    <button @click="increment">Increment</button>

    <p>{{ count }}</p>

    <button @click="decrement">Decrement</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    increment() {
      this.count++;
    },
    decrement() {
      this.count--;
    }
  }
}</script>

<style scoped></style>
