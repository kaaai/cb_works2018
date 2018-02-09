<template>
  <div>
    <Service-Section :item="item" :index="index" v-for="(item,index) in serviceItems"></Service-Section>
  </div>
</template>

<script>
    import ServiceSection from './Service/Section.vue'
    export default {
        data () {
            return {
                serviceItems: [
                    {
                        title: 'Web制作',
                        subTitle: '最新技術でしっかりサポート',
                        heading: 'hoge',
                        text: 'hoge',
                        number: 'num01',
                        thumbnail: '/images/serviceHeading_create.jpg',
                        id: 'web'
                    },
                    {
                        title: 'hoge!',
                        subTitle: '最新技術でしっかり',
                        heading: 'hoge!!',
                        text: 'hoge!!!!!!!!!!',
                        number: 'num02',
                        thumbnail: '/images/serviceHeading_system.jpg',
                        id: 'system'
                    },
                    {
                        title: 'hoge',
                        subTitle: '最新技術でしっかりサポート',
                        heading: 'hoge',
                        text: 'hoge',
                        number: 'num03',
                        thumbnail: '/images/serviceHeading_support.jpg',
                        id: 'advise'
                    },
                    {
                        title: 'hoge',
                        subTitle: '最新技術でしっかりサポート',
                        heading: 'hoge',
                        text: 'hoge',
                        number: 'num04',
                        thumbnail: '/images/serviceHeading_event.jpg',
                        id: 'event'
                    }
                ]
            }
        },
        components: {
            ServiceSection
        }
    }
</script>

<style lang="scss" scoped>
  @import "~assets/scss/layout/_layout.scss";
  @import "~assets/scss/object/component/_container.scss";

</style>

