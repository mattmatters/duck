<template>
    <div class="hello">
      <h1><span v-bind:title="disclaimer">{{ title }}</span></h1>
      <h2>I'm not always a duck...</h2>
      <ul>
          <li>Seasoning</li>
          <li>Bread</li>
      </ul>
      <h2>But today I am</h2>
      <a href="https://en.wikipedia.org/wiki/Steve_Harvey" target="_blank">Steve</a>
    </div>
</template>

<script>
 export default {
   name: 'HelloWorld',
   data() {
     return {
       title: 'Duck Dynasty 2',
       diclaimer: 'You too, duck...',
     };
   },
 };
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
</style>
