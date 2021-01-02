<template>
  <div class="Hero">
    <div class="Hero__mainText">
      <h1>Moynure</h1>
      <h3>Web design</h3>
      <p class="Hero__subtitle py-2 mt-5 pl-3">
        Simple, beautiful, easy-to-use websites
      </p>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.Hero {
  background: url("~assets/img/bg-large.png");
  background-color: rgba($red-3, 0.8);
  background-blend-mode: multiply;
  width: 100%;
  height: 450px;
  display: flex;
  align-items: center;

  .Hero__mainText {
    text-align: left;
    flex: 1 0 auto;
    color: rgba(white, 0.8);

    h1,
    h3 {
      margin-left: 72.5px;
    }

    h3 {
      text-transform: uppercase;
    }

    .Hero__subtitle {
      color: $black-2;
      margin-top: 60px;
      background: rgba(white, 0.8);
      width: 55%;
      margin-left: 72.5px;
      display: inline-block;
      position: relative;

      &::after {
        content: "";
        display: block;
        position: absolute;
        left: 100%;
        top: 50%;
        margin-top: -20px;
        width: 0;
        height: 0;
        border-top: 0 solid transparent;
        border-right: 40px solid transparent;
        border-bottom: 40px solid rgba(white, 0.8);
        border-left: 0 solid transparent;
      }
    }
  }
}
</style>
