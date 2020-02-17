<template lang="pug">
.uk-grid-small.uk-grid-match(uk-grid class="uk-child-width-1-3@m")
  div
    .uk-card.uk-card-primary.uk-card-body
      h3.uk-card-title Reptilians
      p Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      button.uk-button.uk-button-danger.uk-button-large Uffish Thought
  div
    .uk-card.uk-card-default.uk-card-body
      h3.uk-card-title Marsupials
      p Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      button.uk-button.uk-button-secondary.uk-button-large Uffish Thought
  div
    .uk-card.uk-card-secondary.uk-card-body
      h3.uk-card-title Mammals
      p Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      button.uk-button.uk-button-primary.uk-button-large Uffish Thought

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
<style scoped lang="less">

</style>