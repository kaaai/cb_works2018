<template>
  <section class="p-hero">
    <div class="p-hero_content">
      <div class="p-hero_heading">
        「作る」だけじゃなく、<br>
        「伝える」「語り合う」
      </div>
      <div class="p-hero_desc">
        「作る」だけじゃなく、「伝える」「語り合う」
      </div>
      <div class="p-hero_media">
        <div class="c-bg">
          <div class="c-media">
            <div class="c-media_number">01</div>
            <div class="c-media_container">
              <p class="c-media_title">Web制作</p>
              <img src="/images/service_list01.jpg" class="c-media_thumb">
              <p class="c-media_sum">
                最新技術で<br>
                しっかりサポート
              </p>
              <p class="c-media_desc">この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。</p>
            </div>
          </div>
          <div class="c-media">
            <div class="c-media_number">02</div>
            <div class="c-media_container">
              <p class="c-media_title">システム開発</p>
              <img src="/images/service_list02.jpg" class="c-media_thumb">
              <p class="c-media_sum">
                最新技術で<br>
                しっかりサポート
              </p>
              <p class="c-media_desc">この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。</p>
            </div>
          </div>
          <div class="c-media">
            <div class="c-media_number">03</div>
            <div class="c-media_container">
              <p class="c-media_title">技術顧問</p>
              <img src="/images/service_list03.jpg" class="c-media_thumb">
              <p class="c-media_sum">
                最新技術で<br>
                しっかりサポート
              </p>
              <p class="c-media_desc">この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。</p>
            </div>
          </div>
          <div class="c-media">
            <div class="c-media_number">04</div>
            <div class="c-media_container">
              <p class="c-media_title">イベント</p>
              <img src="/images/service_list04.jpg" class="c-media_thumb">
              <p class="c-media_sum">
                最新技術で<br>
                しっかりサポート
              </p>
              <p class="c-media_desc">この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。</p>
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>

<script>
  export default {
  }

</script>

<style lang="scss" scoped>
  .p-hero {
    background-image: none;
  }
  .c-bg{
    position: relative;
    /*background-color: #B43B3E;*/
    height: 81%;
    width: 100%;
    display: inline-flex;
    flex-wrap:wrap;
    justify-content:space-around;
  }

  .p-hero_baseImage {
    width: 100%;
  }
  .p-hero_content {
    height: 107%;
    left: 0;
    top: 0;
    background-color: red;
  }
  .p-hero_heading {
    padding-top: 7%;
    text-align: center;
    color: #FFF;
    font-size: 24px;
    letter-spacing: 6px;
  }
  .p-hero_desc {
    margin-top: 10px;
    text-align: center;
    color: #FFF;
    letter-spacing: 2px;
  }
  .p-hero_media {
    margin-top: 7%;
    padding-top: 7%;
    text-align: center;
  }
  @media screen and (min-width: 768px) {
    .p-hero_media {
      padding-top: 7%;
      margin-top: 0;
      display: flex;
    }
    .c-bg {

    }
    .p-hero {
      position: relative;
      background-image: url('/static/images/service_top.jpg');
      background-repeat: no-repeat;
      background-size: contain;
    }
    .p-hero_content {
      position: relative;
      height: 44%;
      left: 0;
      top: 0;
      z-index: -1000;
    }
  }
</style>
