<template>
  <div>
    <strong>{{title}}</strong>
    <input type="number" placeholder="From price" />
    <input type="number" placeholder="To price" />
    <input type="text" placeholder="Location" />
    <button @click="search">Search</button>
  </div>
</template>

<script>
export default {
  props: {
    title: String
  },
  methods: {
    search() {
      alert("Search is complete.");
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
