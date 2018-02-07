<template>
  <main>
    <page-hero></page-hero>
    <page-service></page-service>
    <page-contact></page-contact>
  </main>
</template>

<script>
  import PageHero from '~/components/Page/Index/Hero.vue'
  import PageService from '~/components/Page/Index/Service.vue'
  import PageContact from '~/components/Page/Index/Contact.vue'

  export default {
    data () {
      return {
        online: true
      }
    },
    components: {
      PageHero,
      PageService,
      PageContact
    }
  }
</script>

<style lang="scss">
  @import "~assets/scss/app.scss";
</style>
