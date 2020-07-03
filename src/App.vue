<template>
  <div id="app" style="text-align: center;">
    <h1>{{ $store.state.count }}</h1>
    <hr>
    <br>
    <CompA />
    <hr>
    <br>
    <CompB />
  </div>
</template>

<script>
import CompA from '@/components/CompA';
import CompB from '@/components/CompB';

export default {
  name: "app",
  components: {
    CompA,
    CompB
  }
}
</script>

<style>

</style>
