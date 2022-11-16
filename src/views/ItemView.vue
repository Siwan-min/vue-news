<template>
  <div>
    <p>{{ this.$store.state.item.title }}</p>
    <div>{{ this.$store.state.item.content }}</div>
  </div>
</template>

<script>
// import { fetchItem } from '../api/index.js';

export default {
  created() {
    const itemId = this.$route.params.id;
    this.$store.dispatch('FETCH_ITEM', itemId);
    //console.log(itemId);
    // fetchItem(1)
    //   .then(response => console.log(response))
    //   .catch(error => console.log(error));
  }
}
</script>

<style>

</style>
