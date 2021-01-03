<template>
  <div class="About">
    <h3 class="About__heading pb-4">About</h3>
    <div class="About__main">
      <div class="About__imgSection">
        <img class="About__img" src="https://placebear.com/250/250" />
        <img src="~assets/img/Curve.png" />
      </div>
      <p class="py-3">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce eget
        dapibus sem, eget aliquam ex. Duis blandit metus ac sagittis imperdiet.
        Curabitur lobortis, tellus in faucibus malesuada, metus nisl accumsan
        nibh, ac porttitor est eros ac quam. Suspendisse posuere neque felis,
        sit amet eleifend risus ultrices ut. Vestibulum tincidunt viverra
        rhoncus. Phasellus sed nulla pharetra, ornare libero nec, varius odio.
        Phasellus eu aliquam<br /><br />
        Sit amet eleifend risus ultrices ut. Vestibulum tincidunt viverra
        rhoncus. Phasellus sed nulla pharetra, ornare libero nec, varius odio.
        Phasellus eu aliquam
      </p>
    </div>
    <Texture class="About__texture" />
  </div>
</template>
<script>
import Texture from "./Texture.vue";
export default {
  components: {
    Texture,
  },
};
</script>
<style lang="scss" scoped>
.About {
  width: 100%;
  color: white;
  background-color: $black-1;
  position: relative;
  height: 675px;

  .About__heading {
    padding-top: 80px;
    padding-left: 72.5px;
  }

  .About__main {
    display: flex;
    justify-content: flex-start;
    padding-left: 72.5px;
    align-items: flex-start;

    .About__img {
      flex: 0 0 250px;
      width: 250px;
      border-radius: 50%;
      margin-right: 60px;
    }

    p {
      max-width: 475px;
    }
  }

  .About__texture {
    height: 675px;
    width: auto;
    position: absolute;
    top: 0;
    right: -8px;
    transform: opacity 0.5;
  }
}
</style>
