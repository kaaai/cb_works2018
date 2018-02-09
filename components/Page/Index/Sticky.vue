<template>
    <div class="p-contact__infoWrapper">
        <a href="" class="p-contact__info">
            <span class="p-contact__infoText">お問合わせはこちら</span>
        </a>
    </div>
</template>

<style lang="scss" scoped>
    @import "~assets/scss/layout/_layout.scss";
    @import "~assets/scss/object/component/_container.scss";

    .p-contact {
        &__infoWrapper {
            display: block;
            position: sticky;
            position: -webkit-sticky;
            bottom: 0;
            width: 100%;
            height: 70px;
            z-index: 10000;
            background: #fff;
            text-align: center;
            line-height: 70px;
            transition: all .3s;

            &:hover {
                background: #C3504F;
                transition: all .3s;

                & > a {
                    color: #fff;
                }
            }
        }

        &__info {
            font-size: 1.6rem;
            color: #C3504F;
            text-decoration: none;

            @include desktop {
                font-size: 1.8rem;
            }
        }

        &__infoText {

            padding-left: 3rem;
            position: relative;
            &::before {
                display: inline-block;
                content: "";
                width: 2rem;
                height: 2rem;
                background: url("/images/icon_mail.svg") no-repeat center;
                background-size: contain;
                position: absolute;
                top: 50%;
                left: .2rem;
                transform: translateY(-1rem);
            }
        }
    }
</style>