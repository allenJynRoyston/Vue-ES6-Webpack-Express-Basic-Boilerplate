<template lang="pug">
  div.container
    h1 Home
    .ui.grid
      .four.wide.column
        center
          card
      .four.wide.column
        center
          card
      .four.wide.column
        center
          card
      .four.wide.column
        center
          card

    button.ui.button(@click='openModal()') Open Modal
    .ui.modal
      i.close.icon
      .header
        | Profile Picture
      .image.content
        .ui.medium.image
          img(src='../assets/images/logo.png')
        .description
          .ui.header We've auto-chosen a profile image for you.
          p
            | We've grabbed the following image from the
            a(href='https://www.gravatar.com', target='_blank') gravatar
            |  image associated with your registered e-mail address.
          p Is it okay to use this photo?
      .actions
        .ui.black.deny.button
          | Nope
        .ui.positive.right.labeled.icon.button
          | Yep, that's me
          i.checkmark.icon
</template>

<script>
export default {
  name: 'home',
  data () {
    return {

    }
  },
  created: function () {

  },
  methods: {
    openModal(){
      console.log("open")
      $('.ui.modal').modal('show')
    }
  }
}
</script>

<style lang="sass" scoped>

</style>
