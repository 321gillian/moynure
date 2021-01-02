<template>
  <div class="Hero">
    <div class="Hero__mainText">
      <h1>Moynure</h1>
      <h3>Web design</h3>
      <p class="Hero__subtitle py-2 mt-5">
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
  height: 650px;
  display: flex;
  align-items: center;

  .Hero__mainText {
    text-align: right;
    flex: 1 0 auto;
    color: white;

    h1,
    h3 {
      margin-right: 250px;
    }

    h3 {
      text-transform: uppercase;
    }

    .Hero__subtitle {
      color: $black-2;
      margin-top: 60px;
      background: white;
      width: 100%;
      padding-right: 250px;
    }
  }
}
</style>
