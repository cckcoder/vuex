<template>
  <div id="coma">
    <h2>{{ $store.getters.getCount }}</h2>
    <button @click="decrease">Del</button>
  </div>
</template>

<script>
export default {
  name: "ComB",
  methods: {
    decrease() {
      this.$store.dispatch('delAction')
    }
  }
}
</script>

<style>

</style>
