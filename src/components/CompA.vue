<template>
  <div id="coma">
    <h2>{{ $store.getters.getCount }}</h2>
    <button @click="increment">Add</button>
  </div>
</template>

<script>
export default {
  name: "ComA",
  methods: {
    increment() {
      this.$store.dispatch('addAction')
    }
  }
}
</script>

<style>

</style>
