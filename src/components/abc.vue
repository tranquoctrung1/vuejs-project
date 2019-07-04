<template>
 <div>
     <h1>{{ hello }}</h1>
 </div>
</template>

<script>
export default {
  name: 'abc',
  props:{
    hello: String,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h1
    {
        color: red
    }

</style>
