<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      I'm a web developer in Tuscaloosa Alabama. I've been coding for about 5 years.<br>
      <br>
      <em>I have experience with:</em>
      <ul>
        <li>WordPress</li>
        <li>JavaScript (Vue.js)</li>
        <li>PHP</li>
        <li>HTML5</li>
        <li>CSS (SCSS)</li>
      </ul>
    </p>
    <h3>Portfolio</h3>
    <ul>
      <li><a href="https://lylessignaturehomes.com" target="_blank" rel="noopener">Lyles Signature Homes</a></li>
      <li><a href="http://myelectriclawns.com" target="_blank" rel="noopener">Electric Lawns</a></li>
    </ul>
    <h3>Personal</h3>
    <ul>
      <li><a href="https://stsymeon.com" target="_blank" rel="noopener">St Symeon Orthodox Church</a></li>
      <li><a href="https://orthodoxtuscaloosa.com" target="_blank" rel="noopener">Orthodox Tuscaloosa</a></li>
    </ul>
    <h3>Social</h3>
    <ul>
      <li><a href="https://www.facebook.com/shea.cole1" target="_blank" rel="noopener">Facebook</a></li>
      <li><a href="https://github.com/robertsheacole" target="_blank" rel="noopener">Github</a></li>
    </ul>
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
<style scoped lang="scss">
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
