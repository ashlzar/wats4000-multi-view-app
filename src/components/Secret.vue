<template>
  <div class="secret">
<h1>{{ message }}</h1>
<ul>
<li><router-link v-bind:to="{ name: 'Home'}">Home</router-link></li>
<li><router-link to="/Survey">Survey</router-link></li>
</ul>
</div>
</template>
<script>
export default {
  name: 'Home',
  data () {
    return {
      message: 'Always check your Devtools!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.error {
  border: 1px solid #aa0000;
  padding: 1rem;
  color: #aa0000;
}
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
