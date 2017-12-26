<template>
  <div>
    <h3>New Quote</h3>
    <button @click="counter++">Increase!</button>
    <p>{{ counter }}</p>
  </div>
</template>

<script>
  export default {
    name: "quote",
    data: function () {
      return {
        counter: 0
      }
    },
    destroyed() {
      console.log('New Destroyed!');
    }
  }
</script>

<style scoped>

</style>
