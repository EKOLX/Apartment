<template>
  <div>
    <section class="apartment" :key="apartment" v-for="apartment in 6">Apartment</section>
  </div>
</template>

<script>
export default {};
</script>

<style>
.apartment {
  display: inline-block;
  height: 100px;
  width: 100px;
  margin: 5px;
  border: 1px solid steelblue;
}
</style>
