<template>
  <div id="app" style="text-align: center;">
    <h1>{{ $store.state.count }}</h1>
    <hr>
    <br>
    <CompA />
  </div>
</template>

<script>
import CompA from '@/components/CompA';

export default {
  name: "app",
  components: {
    CompA
  }
}
</script>

<style>

</style>
