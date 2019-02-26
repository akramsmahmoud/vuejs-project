<template>
<div>
  <h1>{{ name }}</h1>
  <kimo></kimo>
  </div>
</template>

<script>

import comp from './comp.vue';
export default {
  components: {
'kimo': comp
  },
  name: 'app',
  data () {
    return {
      name: 'Do you?'
    }
  }
}
</script>

<style lang="scss" scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
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
h1{
  color:red;
}
</style>
