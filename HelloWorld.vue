<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      A robótica é uma área fascinante que combina engenharia, programação e inovação. 
      Nossas aulas de robótica são projetadas para despertar a curiosidade e desenvolver habilidades essenciais no mundo tecnológico 
      de hoje. Desde a construção de modelos simples até a programação de robôs complexos,
      nossos alunos aprendem de forma prática e divertida, aplicando conceitos de ciência, tecnologia, 
      engenharia e matemática (STEM). Venha explorar o incrível universo da robótica e prepare-se para ser um criador do futuro!
          </p>
        <ul>
      <li><a href="Link1" target="_blank" rel="noopener">Telefone 1</a></li> 
      <li><a href="Link2" target="_blank" rel="noopener">Telefone 2</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Robótica</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">SpikePrime</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Microbit</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">Noticias</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">Aulas De Scracth</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
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
