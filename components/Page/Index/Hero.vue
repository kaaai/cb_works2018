<template>
  <section class="p-hero">
    <h2 class="p-hero__title">chatboxにできること</h2>
    <div class="p-hero__wrap">
      <div class="p-hero__backgound">
        <div class="p-hero__backgoundFilter"></div>
      </div>
      <div class="p-hero__contents">
        <div class="p-hero__catchCopy">
          <h3 class="p-hero__catchCopyMain">「作る」だけじゃなく、<br>「伝える」、「語り合う」</h3>
          <span class="p-hero__catchCopySub">作るだけじゃなく、伝える、語り合う</span>
        </div>
        <ul class="p-hero__lists">
          <li>
            <a href="#" class="p-hero__listItem">
              <div class="p-hero__listItemHeading">Web制作</div>
              <div class="p-hero__listItemThumb"></div>
              <div class="p-hero__listItemDescription">
                <div class="p-hero__listItemDescriptionTitle">最新技術でしっかりサポート</div>
                <span class="p-hero__listItemDescriptionText">この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。</span>
              </div>
            </a>
          </li>
          <li>
            <a href="#" class="p-hero__listItem">
              <div class="p-hero__listItemHeading">Web制作</div>
              <div class="p-hero__listItemThumb" style="background: url('/images/serviceThumb_create.jpg')"></div>
              <div class="p-hero__listItemDescription">
                <div class="p-hero__listItemDescriptionTitle">最新技術でしっかりサポート</div>
                <span class="p-hero__listItemDescriptionText">この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。</span>
              </div>
            </a>
          </li>
          <li>
            <a href="#" class="p-hero__listItem">
              <div class="p-hero__listItemHeading">Web制作</div>
              <div class="p-hero__listItemThumb"></div>
              <div class="p-hero__listItemDescription">
                <div class="p-hero__listItemDescriptionTitle">最新技術でしっかりサポート</div>
                <span class="p-hero__listItemDescriptionText">この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。</span>
              </div>
            </a>
          </li>
          <li>
            <a href="#" class="p-hero__listItem">
              <div class="p-hero__listItemHeading">Web制作</div>
              <div class="p-hero__listItemThumb"></div>
              <div class="p-hero__listItemDescription">
                <div class="p-hero__listItemDescriptionTitle">最新技術でしっかりサポート</div>
                <span class="p-hero__listItemDescriptionText">この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。</span>
              </div>
            </a>
          </li>
        </ul>
      </div>
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
  .p-hero {

    &__title {
      margin-bottom: 2.5rem;
      color: #C3504F;
      text-align: center;
      font-size: 2rem;
      font-weight: bold;
      letter-spacing: 4px;
      @include desktop {
        margin-bottom: 3.5rem;
        font-size: 2.7rem;
        letter-spacing: 6px;
      }
    }

    &__wrap {
      background-color: #C3504F;
      min-height: 800px;
      position: relative;
    }
    &__backgound  {
      background: none;

      @include desktop {
        height: 450px;
        background: url('/images/hero_background.jpg') no-repeat ;
        background-position: center;
        background-size: cover;
      }
    }
    &__backgoundFilter  {
      height: 100%;
      background-color: rgba(195,80,79,.6);
    }
    &__contents {
      @include c-container;
      max-width: 1100px;
      z-index: 1000;
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
      top: 70px;
    }
    &__catchCopy {
      margin-bottom: 100px;
      text-align: center;
      color: #fff;
    }
    &__catchCopyMain {
      display: block;
      margin-bottom: 30px;
      text-align: center;
      font-size: 3rem;
      font-weight: bold;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.4);
      color: inherit;
      line-height: 1.8;
      letter-spacing: 6px;
    }
    &__catchCopySub {
      display: inline-block;
      font-size: 2rem;
      color: inherit;

    }
    &__lists {
      display: flex;
      justify-content: space-between;

    }
    &__listItem {
      display: block;
      border-top: 3px solid #C3504F;
      width: 250px;
      max-width: 250px;
      background: #F5F1F1;
      text-decoration: none;
      color: #393739;
      position: relative;

      &::before {
        display: inline-block;
        content: "01";
        text-align: center;
        line-height: 2.3;
        font-size: 2rem;
        color: #fff;
        width: 70px;
        height: 70px;
        border-radius: 100%;
        background: #C3504F;
        position: absolute;
        z-index: -10;
        top: -40px;
        left: 50%;
        transform: translateX(-35px);
      }
    }
    &__listItemHeading {
      text-align: center;
      padding: 2rem;
      font-size: 1.8rem;
      font-weight: bold;
    }
    &__listItemThumb {
      width: 100%;
      background: url('/images/serviceThumb_create.jpg') no-repeat;
      background-size: cover;
      background-position: center;
      &::before {
        content: "";
        display: block;
        padding-top: 50%;
      }
    }
    &__listItemDescription {
      padding: 2rem;
    }
    &__listItemDescriptionTitle {
      margin-bottom: 1.5rem;
      text-align: center;
      font-size: 1.6rem;
      font-weight: bold;
    }
    &__listItemDescriptionText {
      line-height: 1.8;
    }

  }
</style>
