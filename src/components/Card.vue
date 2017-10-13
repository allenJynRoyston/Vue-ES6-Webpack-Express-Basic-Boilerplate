<template lang="pug">
  .ui.card
    .image
      img(src='../assets/images/logo.png')
    .content
      a.header Hello World
      .meta
        span.date 11/11/2017
      .description
        | Lorem ipsum
    .extra.content
      a
        i.user.icon
        |  Lorem ipsum
</template>

<script>
export default {
  name: 'card',
  data () {
    return {

    }
  }
}
</script>


<style lang="sass" scoped>

</style>
