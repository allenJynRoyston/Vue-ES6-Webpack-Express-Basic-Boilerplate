<template lang="pug">
  .ui.card
    .image
      img(src='../assets/images/logo.png')
    .content
      a.header Kristy
      .meta
        span.date Joined in 2013
      .description
        | Kristy is an art director living in New York.
    .extra.content
      a
        i.user.icon
        |       22 Friends
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
