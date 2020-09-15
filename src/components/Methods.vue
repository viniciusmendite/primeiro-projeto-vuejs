<template>
  <div class="hello">
    <h1>{{message}}</h1>
    <button v-on:onclick="reverseMessage()">reverse</button>
  </div>
</template>

<script>
export default {
  name: 'Methods',
  props: {
  message: String,
    reverseMessage: function(){
      // this.message = this.message.split('').reverse().join('')
      alert('exemplo')
    }
  }
}
</script>