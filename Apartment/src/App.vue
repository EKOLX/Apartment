<template>
  <div id="app">
    <Header title="Rent Apartment" class="header" />
    <Apartments />
  </div>
</template>

<script>
import Header from "./components/shared/Header.vue";
import Apartments from "./components/Apartments.vue";

export default {
  name: "app",
  components: {
    Header,
    Apartments
  }
};
</script>

<style>
#app {
  padding: 10px;
}
.header {
  margin-bottom: 10px;
}
</style>
