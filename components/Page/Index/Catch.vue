<template>
  <section class="p-catch">
    <img class="p-catch_logo" src="/images/logo.jpg" alt="chatboxロゴ">
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
    margin: 7% 0;
    width: 17%;
  }
  .p-catch_title {
    margin-top: 10px;
    margin-bottom: 16px;
    color: #B43B3E;
    font-size: 26px;
    letter-spacing: 6px;
  }
  .p-catch_angle {
    position: absolute;
    top: 0;
    left: 0;
    width: 0;
    height: 0;
    border: 40px solid transparent;
    border-top: 40px solid #B43B3E;
    border-left: 40px solid #B43B3E;
  }
  @media screen and (min-width: 768px) {
    .p-catch_logo{
      margin: 3% 0;
      width: 5%;  }
  }
</style>
