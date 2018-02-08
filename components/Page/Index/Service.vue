<template>
  <div>
    <!--TODO .p-sectionを繰り返す。偶数のものには.is-coloredをつける（テキストとサムネイルは入れ替え、beforeのcontentの数字は変更可能？）-->
    <section class="p-service">
      <div class="p-service__inner">
        <div class="p-service__heading">
          <div class="p-service__headingBackgound" style="background-image: url('/images/serviceHeading_create.jpg');">
            <div class="p-service__headingFilter">
              <div class="p-service__headinginner">
                <div class="p-service__headingTitleWrap">
                  <div class="p-service__headingTitle">Web制作</div>
                  <div class="p-service__headingSubTitle">最新技術でしっかりサポート</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="p-service__contentsInner">
          <ul class="p-service__problemLists">
            <li class="p-service__problemListsItem">スマートフォン対応がしたい</li>
            <li class="p-service__problemListsItem">SPAにしたい</li>
            <li class="p-service__problemListsItem">複雑なサイトを技術で解決したい</li>
            <li class="p-service__problemListsItem">SPAにしたい</li>
          </ul>
          <div class="p-service__description">
            <h3 class="p-service__descriptionTitle">複雑化するシステム構築の課題を、 最新の制作技術でしっかりサポート</h3>
            <div class="p-service__descriptionText">
              <span class="text-blod">複雑化するシステム構築の課題</span>を、
              <span class="text-blod">最新の制作技術でしっかりサポート</span>多様化するニーズや、複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート。
              <span class="text-blod">Web制作に関するあらゆる相談に対応出来るよう、経験豊富なスタッフが親身に対応にあたります。</span>
            </div>
          </div>
          <div class="p-service__example">
            <div class="p-service__exampleHeading">導入事例</div>
            <ul class="p-service__exampleList">
              <li class="p-service__exampleListItem">Webサイト制作</li>
              <li class="p-service__exampleListItem">Webサイト制作</li>
              <li class="p-service__exampleListItem">Webサイト制作</li>
              <li class="p-service__exampleListItem">Webサイト制作</li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <section class="p-service is-colored">
      <div class="p-service__inner">
        <div class="p-service__heading">
          <div class="p-service__headingBackgound" style="background-image: url('/images/serviceHeading_create.jpg');">
            <div class="p-service__headingFilter">
              <div class="p-service__headinginner">
                <div class="p-service__headingTitleWrap">
                  <div class="p-service__headingTitle">Web制作</div>
                  <div class="p-service__headingSubTitle">最新技術でしっかりサポート</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="p-service__contentsInner">
          <ul class="p-service__problemLists">
            <li class="p-service__problemListsItem">スマートフォン対応がしたい</li>
            <li class="p-service__problemListsItem">SPAにしたい</li>
            <li class="p-service__problemListsItem">複雑なサイトを技術で解決したい</li>
            <li class="p-service__problemListsItem">SPAにしたい</li>
          </ul>
          <div class="p-service__description">
            <h3 class="p-service__descriptionTitle">複雑化するシステム構築の課題を、 最新の制作技術でしっかりサポート</h3>
            <div class="p-service__descriptionText">
              <span class="text-blod">複雑化するシステム構築の課題</span>を、
              <span class="text-blod">最新の制作技術でしっかりサポート</span>多様化するニーズや、複雑化するシステム構築の課題を、最新の制作技術でしっかりサポート。
              <span class="text-blod">Web制作に関するあらゆる相談に対応出来るよう、経験豊富なスタッフが親身に対応にあたります。</span>
            </div>
          </div>
          <div class="p-service__example">
            <div class="p-service__exampleHeading">導入事例</div>
            <ul class="p-service__exampleList">
              <li class="p-service__exampleListItem">Webサイト制作</li>
              <li class="p-service__exampleListItem">Webサイト制作</li>
              <li class="p-service__exampleListItem">Webサイト制作</li>
              <li class="p-service__exampleListItem">Webサイト制作</li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  export default {
  }
</script>

<style lang="scss" scoped>
  @import "~assets/scss/layout/_layout.scss";
  @import "~assets/scss/object/component/_container.scss";
  .p-service.is-colored {
    background: #FAF7F7;

    .p-service__exampleHeading {
      background: #fff ;
    }
    .p-service__problemListsItem  {
      background: #fff;
      &::after {
        border-color: #fff transparent transparent transparent;
      }
    }
  }
  .p-service {
    padding: 50px 0 30px;

    @include desktop {
      padding: 80px 0 60px;
    }

    &__inner {
      @include desktop {
        @include c-container;
        box-sizing: border-box;
      }
    }
    &__heading {
      margin-bottom: 25px;
      width: 100%;
      position: relative;
      z-index: 20;

      &::before {
        display: inline-block;
        content: "01";
        text-align: center;
        line-height: 2.3;
        font-size: 1.8rem;
        color: #fff;
        width: 70px;
        height: 70px;
        border-radius: 100%;
        background: #C3504F;
        position: absolute;
        top: -35px;
        left: 50%;
        transform: translateX(-35px);
        z-index: -10;
        @include desktop {
          border: none;
          width: 80px;
          height: 80px;
          font-size: 2rem;
          top: -40px;
          left: 50%;
          transform: translateX(-35px);
        }
      }
    }
    &__headingBackgound {
      background-repeat: no-repeat ;
      background-position: center;
      background-size: cover;
    }
    &__headingFilter {
      box-sizing: border-box;
      padding: 0 3rem;
      width: 100%;
      height: 100px;
      background: linear-gradient(left, rgba(195,80,79,0.7) 0%, rgba(195,80,79,0.7) 1%, rgba(195,80,79,0.01) 98%, rgba(195,80,79,0) 100%);;
      @include desktop {
        height: 150px;
      }
    }
    &__headingTitleWrap {
      color: #fff;
      @include desktop {
        line-height: 3.5;
      }
    }
    &__headingTitle {
      display: block;
      padding-top: 2.2rem;
      font-size: 2.5rem;
      font-weight: bold;
      @include desktop {
        display: inline-block;
        font-size: 3rem;
      }
    }
    &__headingSubTitle {
      display: block;
      margin-left: 0;
      font-size: 1.4rem;
      @include desktop {
        display: inline-block;
        margin-left: 1.5rem;
      }
    }
    &__contentsInner{
      @include c-container;
    }
    &__problemLists {
      display: flex;
      justify-content: space-between;
      box-sizing: border-box;
      margin-bottom: 15px;
      align-items: flex-start;
      flex-wrap: wrap;
      @include desktop {
        flex-wrap: nowrap;
        margin-bottom: 20px;
      }
    }
    &__problemListsItem  {
      margin: 0 1px;
      padding: 1.3rem 2.5rem;
      width: auto;
      text-align: center;
      font-size: 1.1rem;
      font-weight: bold;
      border-radius: 4px;
      background: #fbf3f3;
      position: relative;

      &:not(:last-of-type){
        margin-bottom: 2rem;
      }

      @include desktop {
        margin: 0 2px;
        margin-bottom: 0;
        font-size: 1.5rem;
      }

      &::after {
        content: "";
        display: inline-block;
        width: 0;
        height: 0;
        border-style: solid;
        border-width: 10px 8px 0 8px;
        border-color: #fbf3f3 transparent transparent transparent;
        position: absolute;
        bottom: -8px;
        left: 50%;
        transform: translateX(-4px);
        @include desktop {
          border-width: 14px 12px 0 12px;
          bottom: -13px;
          transform: translateX(-6px);
        }
      }
    }
    &__description {
      margin-bottom: 40px;
    }
    &__descriptionTitle {
      margin-bottom: 2.5rem;
      font-size: 2rem;
      font-weight: bold;
      color: #C3504F;
      letter-spacing: 3px;
      @include desktop {
        font-size: 2.5rem;
      }
    }
    &__descriptionText {
      line-height: 2.3;
      font-size: 1.4rem;
      @include desktop {
        font-size: 1.6rem;
      }
    }
    &__example {
      display: flex;
      margin-bottom: 40px;
      align-items:center;
      flex-wrap: wrap;
      @include desktop {
        flex-wrap: nowrap;
      }
    }
    &__exampleHeading {
      box-sizing: border-box;
      margin-bottom: 1rem;
      padding: 1rem 4rem;
      width: 100%;
      background: #fbf3f3 ;
      text-align: center;
      font-size: 1.4rem;
      @include desktop {
        margin-bottom: 0;
        padding: 1rem 4rem;
        width: auto;
        font-weight: normal;
      }
    }
    &__exampleList {
      box-sizing: border-box;
      padding-left: 0;
      @include desktop {
        padding-left: 20px;
      }
    }
    &__exampleListItem {
      display: inline-block;
      font-weight:bold;
      @include desktop {

      }
      &::after {
        display: inline-block;
        content: "/";
        padding: .5rem 1rem;
      }
    }
  }
</style>

