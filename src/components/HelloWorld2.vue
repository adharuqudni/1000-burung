<template>
<h3>ini helloword {{angka}}</h3>
</template>

<script>
export default {
  name: 'HelloWorld2',
  props: {
    angka: Number
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3{
  color: red;
}
</style>
