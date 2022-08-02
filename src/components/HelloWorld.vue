<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Para ponerte en contacto con nosotros por favor hacerlo a través de <a href="https://www.linkedin.com/in/antonia-brahm-justiniano-12141620/">Antonia Brahm</a>.
    </p>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
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
