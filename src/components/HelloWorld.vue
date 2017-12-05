<template>
  <div class="welcome">
    <h1>{{ msg }}</h1>
    <img src="../assets/bitmoji-bijkler.png"/>
  </div>
</template>

<script>
export default {
  name: 'Aventine Solutions',
  data () {
    return {
      msg: 'Aventine Solutions'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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

.welcome {
  width: 66%;
  text-align: center;
  border: 0.5em groove darkgrey;
  background-color: cornsilk;
}

.welcome h1 {
  color: darkorange;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 250%;
}

</style>
