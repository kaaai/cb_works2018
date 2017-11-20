<template>
  <section class="p-catch">
    <div class="p-catch_angle">
      <!--TODO 一旦うまくいかないので無視-->
      <!--<div class="p-catch_angle_logo"></div>-->
    </div>
    <img class="p-catch_logo" src="/images/logo.png" alt="chatboxロゴ">
    <h1 class="p-catch_title">chatboxにできること</h1>
  </section>
</template>

<script>
export default {
}

</script>

<style lang="scss" scoped>
  .p-catch {
    text-align: center;
  }
  .p-catch_logo {
    margin-top: 7%;
    width: 17%;
  }
  .p-catch_title {
    margin: 7% 0;
    color: #B43B3E;
    letter-spacing: 3px;
  }
  .p-catch_angle {
    position: fixed;
    top: 0;
    left: 0;
    width: 0;
    height: 0;
    border: 40px solid transparent;
    border-top: 40px solid #B43B3E;
    border-left: 40px solid #B43B3E;
  }
    @media screen and (min-width: 768px) {
      .p-catch_logo {
        margin-top: 5%;
        width: 5%;
      }
      .p-catch_title{
        margin: 3% 0;
      }
    }
</style>
