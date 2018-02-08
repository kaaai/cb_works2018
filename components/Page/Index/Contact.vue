<template>
    <section class="p-contact">
        <div class="p-contact__info">
            <span>お問合わせはこちら</span>
        </div>
        <div class="p-contact__inner">
            <div class="p-contact__toChatbox">Webにまつわるお悩み、<br>ご相談はお気軽にchatboxまで。</div>
            <div class="p-contact__formContents">
                <a class="p-contact__button" href="/contact">お問い合わせフォームへ </a>
                <div class="p-contact__tel">
                    <p>お電話でのお問い合わせ</p>
                    <a href="tel:050-3555-1212">050-3555-1212</a>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {}

</script>

<style lang="scss" scoped>
    @import "~assets/scss/layout/_layout.scss";
    @import "~assets/scss/object/component/_container.scss";

    .p-contact__info {
        font-size: 1.6rem;
        padding: 2%;
        width: 100%;
        background-color: #fff;
        color: #C3504F;
        text-align: center;
        position: relative;
        @include desktop {
            padding: 1%;
        }

        &::after {
            content: "";
            display: inline-block;
            width: 0;
            height: 0;
            border-style: solid;
            border-width: 22px 16px 0 16px;
            border-color: #FFF transparent transparent transparent;
            position: absolute;
            bottom: -20px;
            left: 44%;
            -webkit-transform: translateX(-4px);
            transform: translateX(-4px);
            @include desktop {
                border-width: 40px 32px 0 32px;
                bottom: -40px;
                left: 48%;
            }
        }
        span {
            background: url("/images/icon_mail.svg") no-repeat;
            background-size: 11%;
            background-position: left;
            padding-left: 7%;
            @include desktop {
                font-size: 1.4rem;
                padding-left: 2%;
                background-size: contain;
            }
        }
    }
    .p-contact {
        background: #C3504F;
        color: #fff;
        text-align: center;
        padding: 0 0 6% 0;
        &__inner {
            @include c-container;
        }
        &__toChatbox {
            font-size: 1.4rem;
            letter-spacing: .2em;
            line-height: 2;
            margin: 15% 0 5%;
            @include desktop {
                font-size: 3rem;
                margin: 7% 0 5%;
            }
        }
        &__formContents {
            @include desktop {
                display: flex;
                flex-direction: row;
                padding: 0 3% 0 6%;
                margin: 0 auto;
            }
        }
        &__tel {
            font-size: 1.4rem;
            padding: 5% 0;
            letter-spacing: .1em;
            line-height: 1.8;
            @include desktop {
                font-size: 1.8rem;
                padding: 1% 5%;
            }
            a {
                font-weight: bold;
                color: #FFF;
                text-decoration: none;
                font-size: 2.3rem;
                letter-spacing: .2rem;
                @include desktop {
                    margin-bottom: 4%;
                    font-size: 2.9rem;
                }
            }
        }
        &__button {
            display: inline-block;
            padding: 2rem;
            width: 77%;
            margin: 4% 0;
            text-align: center;
            border-radius: 4px;
            color: #C3504F;
            font-size: 1.5rem;
            font-weight: bold;
            background: #FFF;
            text-decoration: none;
            position: relative;
            transition: all .5s;
            @include desktop {
                width: 100%;
                max-width: 450px;
                margin: 0;
                padding: 4rem;
                font-size: 2rem;
            }
            &:hover {
                opacity: .8;
                transition: all .5s;
                &::before {
                    right: .2rem;
                    transition: all .5s;
                }
            }
            &::before {
                content: "";
                display: inline-block;
                width: 1.4rem;
                height: 1.4rem;
                background-image: url("/images/icon_arrow.svg");
                background-repeat: no-repeat;
                background-size: contain;
                background-position: center;
                position: absolute;
                right: .7rem;
                top: 50%;
                transform: translateY(-50%);
                transition: all .5s;
                @include desktop {
                    width: 3rem;
                    height: 2.2rem;
                    right: 2rem;
                }
            }
        }
    }
</style>
