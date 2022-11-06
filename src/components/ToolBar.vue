<template>
  <div class="header">
    <router-link to="/news">News</router-link> |
    <router-link to="/ask">Ask</router-link> | 
    <router-link to="/jobs">Jobs</router-link>
  </div>
</template>

<style scoped>
.header {
  background-color: #42b883;
  color: white;
  padding: 8px 8px 8px 25px;
  display: flex;
  align-items: center;
}

.header .router-link-exact-active {
    color: #35495e;
}

.header a {
    color: white;
}

</style>