<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/docs" target="_blank">Vue_CLI_Docs</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">Awesome_Vue</a></li>
    </ul>
    <h3>Old Projects</h3>
    <ul>
      <li><a href="https://github.com/Tor020/VueBulmaSassBP/tree/master/scripts" target="_blank">Vue_Notes_Good Example</a></li>
      <li><a href="https://github.com/Tor020/Sectioned-Vue-Notes" target="_blank">Vue_Mediocre Example</a></li>
    </ul>
    <h3>Cheat Sheets / Docs</h3>
    <ul>
      <li><a href="https://devhints.io/vue" target="_blank">Dev_Hints</a></li>
      <li><a href="https://vuejs-tips.github.io/cheatsheet/" target="_blank">Cheat_Sheet_Docs</a></li>
      <li><a href="https://laracasts.com/series/learn-vue-2-step-by-step/" target="_blank">Laracasts</a></li>
      <li><a href="https://vuejs.org/v2/guide/" target="_blank">Core_Vue_Docs</a></li>
      <li><a href="http://devdocs.io/vue~2-guide/" target="_blank">Dev_Docs</a></li>
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

</style>
