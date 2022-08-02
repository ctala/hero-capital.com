<template>
  <div class="hello">

    <h1 class="text-3xl font-bold underline">
    
  </h1>
    <p>
    </p>

      <div class="bg-indigo-700">
    <div class="max-w-2xl mx-auto text-center py-16 px-4 sm:py-20 sm:px-6 lg:px-8">
      <h2 class="text-3xl font-extrabold text-white sm:text-4xl">
        <span class="block">{{ msg }}</span>
      </h2>
      <p class="mt-4 text-lg leading-6 text-indigo-200">Para ponerte en contacto con nosotros por favor hacerlo a través de</p>
      <a  target="_blank" href="https://www.linkedin.com/in/antonia-brahm-justiniano-12141620/" class="mt-8 w-full inline-flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-indigo-600 bg-white hover:bg-indigo-50 sm:w-auto"> Antonia Brahm </a>
    </div>
  </div>
      
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
/* h3 {
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
} */
</style>
