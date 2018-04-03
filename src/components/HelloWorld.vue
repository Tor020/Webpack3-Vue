<template lang = "pug">
.hello

  h1 {{ msg }}

  ul
    li
      a(href='https://github.com/vuejs/vue-cli/tree/dev/docs' target='_blank') Vue_CLI_Docs
    li
      a(href='https://github.com/vuejs/awesome-vue' target='_blank') Awesome_Vue
      
  h3 Old Projects

  ul
    li
      a(href='https://github.com/Tor020/VueBulmaSassBP/tree/master/scripts' target='_blank') Vue_Notes_Good Example
    li
      a(href='https://github.com/Tor020/Sectioned-Vue-Notes' target='_blank') Vue_Mediocre Example

  h3 Cheat Sheets / Docs

  ul
    li
      a(href='https://devhints.io/vue' target='_blank') Dev_Hints
    li
      a(href='https://vuejs-tips.github.io/cheatsheet/' target='_blank') Cheat_Sheet_Docs
    li
      a(href='https://vuejs.org/v2/guide/' target='_blank') Core_Vue_Docs
    li
      a(href='http://devdocs.io/vue~2-guide/' target='_blank') Dev_Docs
    li
      a(href='https://devhints.io/pug') Devhints Pug cheatsheet
    li
      a(href='https://pugjs.org/language/attributes.html') Pug Reference Page

  h3 Guide

  ul
    li
      a(href='https://laracasts.com/series/learn-vue-2-step-by-step/' target='_blank') Laracasts
  h3 Tools

  ul
    li
      a(href='https://pughtml.com/') Pug to HTML
    li
      a(href='https://html-to-pug.com/') HTML to Pug

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
