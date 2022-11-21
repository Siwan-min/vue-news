<template>
  <div>
    <list-item></list-item>    
  </div>
</template>

<script>
import ListItem from '../components/ListItem.vue'

export default {
  // created() {
  //   this.$store.dispatch('FETCH_NEWS');
  //   // fetchJobsList()
  //   //   .then(response => this.jobs = response.data)
  //   //   .catch(error => console.log(error));
  // },
  components: { ListItem },
}

</script>
