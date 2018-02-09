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
                        balloons: [
                          'スマートフォン対応がしたい。',
                          'スマートフォン対応がしたい。',
                          'スマートフォン対応がしたい。',
                          'スマートフォン対応がしたい。'
                        ],
                        heading: '複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート',
                        texts: [
                            '複雑化するシステム構築の課題',
                            'を、',
                            '最新の制作技術でしっかりサポート',
                            '多様化するニーズや、複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート。Web制作に関するあらゆる相談に対応出来るよう、',
                            '経験豊富なスタッフが親身に対応にあたります。'
                        ],
                        number: 'num01',
                        thumbnail: '/images/serviceHeading_create.jpg',
                        id: 'web',
                        examples: [
                            'Webサイト制作',
                            'Webサイト制作',
                            'Webサイト制作',
                            'Webサイト制作',
                        ]
                    },
                    {
                        title: 'システム開発',
                        subTitle: '最新技術でしっかりサポート',
                        balloons: [
                            'スマートフォン対応がしたい。',
                            'スマートフォン対応がしたい。',
                            'スマートフォン対応がしたい。',
                            'スマートフォン対応がしたい。'
                        ],
                        heading: '複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート',
                        texts: [
                            '複雑化するシステム構築の課題',
                            'を、',
                            '最新の制作技術でしっかりサポート',
                            '多様化するニーズや、複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート。Web制作に関するあらゆる相談に対応出来るよう、',
                            '経験豊富なスタッフが親身に対応にあたります。'
                        ],
                        number: 'num02',
                        thumbnail: '/images/serviceHeading_system.jpg',
                        id: 'system',
                        examples: [
                            'Webサイト制作',
                            'Webサイト制作',
                            'Webサイト制作',
                            'Webサイト制作',
                        ]
                    },
                    {
                        title: '技術顧問',
                        subTitle: '最新技術でしっかりサポート',
                        balloons: [
                            'スマートフォン対応がしたい。',
                            'スマートフォン対応がしたい。',
                            'スマートフォン対応がしたい。',
                            'スマートフォン対応がしたい。'
                        ],
                        heading: '複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート',
                        texts: [
                            '複雑化するシステム構築の課題',
                            'を、',
                            '最新の制作技術でしっかりサポート',
                            '多様化するニーズや、複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート。Web制作に関するあらゆる相談に対応出来るよう、',
                            '経験豊富なスタッフが親身に対応にあたります。'
                        ],
                        number: 'num03',
                        thumbnail: '/images/serviceHeading_support.jpg',
                        id: 'advise',
                        examples: [
                            'Webサイト制作',
                            'Webサイト制作',
                            'Webサイト制作',
                            'Webサイト制作',
                        ]
                    },
                    {
                        title: 'イベント',
                        subTitle: '最新技術でしっかりサポート',
                        balloons: [
                            'スマートフォン対応がしたい。',
                            'スマートフォン対応がしたい。',
                            'スマートフォン対応がしたい。',
                            'スマートフォン対応がしたい。'
                        ],
                        heading: '複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート',
                        texts: [
                            '複雑化するシステム構築の課題',
                            'を、',
                            '最新の制作技術でしっかりサポート',
                            '多様化するニーズや、複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート。Web制作に関するあらゆる相談に対応出来るよう、',
                            '経験豊富なスタッフが親身に対応にあたります。'
                        ],
                        number: 'num04',
                        thumbnail: '/images/serviceHeading_event.jpg',
                        id: 'event',
                        examples: [
                            'Webサイト制作',
                            'Webサイト制作',
                            'Webサイト制作',
                            'Webサイト制作',
                        ]
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

