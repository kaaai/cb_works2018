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
        <div class="c-bg"></div>
        <div class="c-media">
          <div class="c-media_number">01</div>
          <div class="c-media_container">
            <p class="c-media_title">Web制作</p>
            <img src="https://placehold.jp/150x150.png" class="c-media_thumb">
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
            <img src="https://placehold.jp/150x150.png" class="c-media_thumb">
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
            <img src="https://placehold.jp/150x150.png" class="c-media_thumb">
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
            <img src="https://placehold.jp/150x150.png" class="c-media_thumb">
            <p class="c-media_sum">
              最新技術で<br>
              しっかりサポート
            </p>
            <p class="c-media_desc">この文章はダミーです。文字の大きさ、量、字間、行間等を確認するために入れています。この文章はダミーです。</p>
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
    position: relative;
    height: 1130px;
    background-image: url('http://placeimg.com/640/340/people/sepia');
    background-repeat: no-repeat;
    background-size: contain;
    z-index: 100;
  }
  .c-bg{
    background-position: top;
    position: absolute;
  }

  .p-hero_baseImage {
    width: 100%;
  }
  .p-hero_content {
    height: 107%;
    left: 0;
    top: 0;
    background: #b43b3e;
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
    }
    .p-hero_media {
      margin-top: 0;
    }
    .c-bg {
      position: absolute;
      background-color: #B43B3E;
      height: 81%;
      width: 100%;
      z-index: -100;
      margin-top: 13%;
    }
    .p-hero_content {
      position: absolute;
      height: 44%;
      left: 0;
      top: 0;
      background: rgba(195,80,79,0.65);
    }
  }
</style>
