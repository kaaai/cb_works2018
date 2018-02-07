<template>
  <main>
    <page-hero></page-hero>
    <page-website></page-website>
    <!--<page-system></page-system>-->
    <!--<page-advisor></page-advisor>-->
    <!--<page-event></page-event>-->
  </main>
</template>

<script>
  import PageHero from '~/components/Page/Index/Hero.vue'
  import PageWebsite from '~/components/Page/Index/Website.vue'
//  import PageSystem from '~/components/Page/Index/System.vue'
//  import PageAdvisor from '~/components/Page/Index/Advisor.vue'
//  import PageEvent from '~/components/Page/Index/Event.vue'

  export default {
    data () {
      return {
        online: true
      }
    },
    components: {
      PageHero,
      PageWebsite,
//      PageSystem,
//      PageAdvisor,
//      PageEvent
    }
  }
</script>

<style lang="scss">
  @import "~assets/scss/app.scss";
</style>
