<template>
  <section class="p-catch">
    <img class="p-catch_logo" src="/images/logo.svg" alt="chatboxロゴ">
    <div class="p-catch_title">chatboxにできること</div>
    <div class="p-catch_angle">
    <!--TODO 一旦うまくいかないので無視-->
    <!--<div class="p-catch_angle_logo"></div>-->
  </div>
  </section>
</template>

<script>
export default {
}

</script>

<style lang="scss" scoped>
  .p-catch {
    position: relative;
    text-align: center;
  }
  .p-catch_logo {
    margin: 9% 0 2%;
    width: 16%;
    @media screen and (min-width: 768px) {
      margin: 7% 0;
      width: 17%;
    }
  }
  .p-catch_title {
    margin-top: 10px;
    margin-bottom: 16px;
    color: #C3504F;
    font-size: 23px;
    font-weight: 600;
    letter-spacing: 6px;
    @media screen and (min-width: 768px) {
        font-size: 25px;
        margin-bottom: 2%;

    }
  }
  .p-catch_angle {
    position: absolute;
    top: 0;
    left: 0;
    width: 0;
    height: 0;
    border: 40px solid transparent;
    border-top: 40px solid #C3504F;
    border-left: 40px solid #C3504F;
    background-image: url('/static/images/icon_chatbox-white.svg');
    background-position: top;
  }
  @media screen and (min-width: 768px) {
    .p-catch_logo{
      margin: 3% auto 2%;
      width: 6%;
    }
  }
  .c-block {
    padding-top: 8%;
  }
</style>
