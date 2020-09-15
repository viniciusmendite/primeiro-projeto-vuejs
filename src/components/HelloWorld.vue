<template>
  <div class="hello">
    <h1 v-bind:title="tagMessage">{{`Meu nome é ${name.toUpperCase()} e tenho ${Number(age) +1} anos`}}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    name: String,
    age: Number,
    tagMessage: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
