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
    </div>
    <div class="p-hero_media">
      <div class="c-media_box">
        <div class="c-media">
          <div class="c-media_number"><span>01</span></div>
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

  </section>
</template>

<script>
  export default {
  }

</script>

<style lang="scss" scoped>
  .c-bg{
    background-position: top;
    position: absolute;
  }
  .p-hero_baseImage {
    width: 100%;
  }
  .p-hero_content {
    height: 500px;
    width: 100%;
    background-color: #B43B3E;
    position: absolute;
    z-index: 1000;
  }
  .p-hero_heading {
    padding-top: 7%;
    text-align: center;
    color: #FFF;
    letter-spacing: 4px;
    font-size: 220%;
  }
  .p-hero_desc {
    font-size: 50%;
    letter-spacing: 3px;
    color: #FFF;
    text-align: center;
    margin-top: 5%;
    padding-bottom: 5%;
  }
  .p-hero_media {
    background-color: #B43B3E;
    padding-bottom: 4%;
  }
    .p-hero{
      overflow: hidden;
    }
    .p-hero_media {
      text-align: center;
      width: 100%;
    }
    .p-hero_content {
      height: 0;
      width: 100%;
      background-color: #b43b3e;
      z-index: 1000;
    }

  @media screen and (min-width: 768px) {
    .p-hero_desc {
      font-size: 150%;
    }
    .p-hero_content {
      position: absolute;
      background-image: url("/static/images/service_top.jpg");
      background-repeat: no-repeat;
      background-size: contain;
      height: 500px;
    }
  }
</style>
