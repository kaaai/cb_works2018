<template>
  <main>
    <page-hero></page-hero>
    <page-service></page-service>
    <sticky></sticky>
    <page-contact></page-contact>
  </main>
</template>

<script>
  import PageHero from '~/components/Page/Index/Hero.vue'
  import PageService from '~/components/Page/Index/Service.vue'
  import Sticky from '~/components/Page/Index/Sticky.vue'
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
      Sticky,
      PageContact
    }
  }
</script>

<style lang="scss">
  @import "~assets/scss/app.scss";
</style>
