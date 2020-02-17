<template lang="pug">
#app
  nav.uk-navbar-container.uk-margin(uk-navbar uk-sticky)
    .uk-navbar-left
      a.uk-navbar-item.uk-logo(href='#') 
        i.fas.fa-sun.fa-2x
        | &nbsp; Engenho Novo LLC
      ul.uk-navbar-nav
        li
          a(href='#')
            span.uk-icon.uk-margin-small-right(uk-icon='icon: fork') &nbsp; In Principio
        li
          a(href='#')
            span.uk-icon.uk-margin-small-right(uk-icon='icon: fork') &nbsp; In Media Res

      .uk-navbar-item
        div
          button.uk-button.uk-button.uk-button-secondary Impressão
      .uk-navbar-item
        form(action='javascript:void(0)')
          input.uk-input.uk-form-width-small(type='text' placeholder='Guglear')
          button.uk-button.uk-button-default Expressão
  router-view

</template>

<script>
  import UIkit from 'uikit';
  import Icons from 'uikit/dist/js/uikit-icons';
  UIkit.use(Icons);
  export default {
      name: 'App',
  };
</script>


<style>
@import "../node_modules/uikit/dist/css/uikit.css";
@import url("https://fonts.googleapis.com/css?family=News+Cycle|Material+Icons");

html, #app, body {
  font-family: 'News Cycle', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
