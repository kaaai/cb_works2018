<template>
  <section class="p-service">
    <div class="p-service__heading">
      <div class="p-service__headingBackgound">
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
    </div>
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
  </section>
</template>

<script>
  export default {
  }
</script>

<style lang="scss" scoped>
  @import "~assets/scss/layout/_layout.scss";
  @import "~assets/scss/object/component/_container.scss";
  .p-service {
    @include desktop {
      @include c-container;
      box-sizing: border-box;
      margin-bottom: 60px;
    }
    &__heading {
      margin-bottom: 20px;
      width: 100%;
      position: relative;
      z-index: 20;

      &::before {
        display: inline-block;
        content: "01";
        text-align: center;
        line-height: 2.3;
        font-size: 1.4rem;
        color: #fff;
        width: 50px;
        height: 50px;
        border-radius: 100%;
        background: #C3504F;
        position: absolute;
        top: -30px;
        left: 50%;
        transform: translateX(-25px);
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
      background: url('/images/serviceHeading_create.jpg') no-repeat ;
      background-position: center;
      background-size: cover;
    }
    &__headingFilter {
      box-sizing: border-box;
      padding: 0 3rem;
      width: 100%;
      height: 150px;
      background: linear-gradient(left, rgba(195,80,79,0.7) 0%, rgba(195,80,79,0.7) 1%, rgba(195,80,79,0.01) 98%, rgba(195,80,79,0) 100%);;
    }
    &__headingTitleWrap {
      color: #fff;
      line-height: 5;
    }
    &__headingTitle {
      display: inline-block;
      font-size: 3rem;
      font-weight: bold;
      vertical-align: middle;
    }
    &__headingSubTitle {
      margin-left: 1.5rem;
      display: inline-block;
    }
    &__contentsInner{
      @include c-container;
    }
    &__problemLists {
      display: flex;
      justify-content: space-between;
      box-sizing: border-box;
      margin-bottom: 40px;

    }
    &__problemListsItem  {
      padding: 1.3rem 2.5rem;
      width: auto;
      text-align: center;
      font-weight: bold;
      border-radius: 4px;
      background: #fbf3f3;
      position: relative;
      &::after {
        content: "";
        display: inline-block;
        width: 0;
        height: 0;
        border-style: solid;
        border-width: 14px 12px 0 12px;
        border-color: #fbf3f3 transparent transparent transparent;
        position: absolute;
        bottom: -13px;
        left: 50%;
        transform: translateX(-6px);
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
      letter-spacing: 2px;
    }
    &__descriptionText {
      line-height: 2.3;
    }
    &__example {
      display: flex;
      margin-bottom: 40px;
      align-items:center;
    }
    &__exampleHeading {
      padding: 1rem 4rem;
      background: #fbf3f3 ;
    }
    &__exampleList {
      box-sizing: border-box;
      padding-left: 20px;
    }
    &__exampleListItem {
      display: inline-block;
      &::after {
        display: inline-block;
        content: "/";
        padding: 1rem;
      }
    }
  }
</style>

