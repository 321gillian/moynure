<template>
  <div class="About">
    <h3 class="About__heading pb-4">About</h3>
    <div class="About__main">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce eget
        dapibus sem, eget aliquam ex. Duis blandit metus ac sagittis imperdiet.
        Curabitur lobortis, tellus in faucibus malesuada, metus nisl accumsan
        nibh, ac porttitor est eros ac quam. Suspendisse posuere neque felis,
        sit amet eleifend risus ultrices ut. Vestibulum tincidunt viverra
        rhoncus. Phasellus sed nulla pharetra, ornare libero nec, varius odio.
        Phasellus eu aliquam
      </p>
    </div>
    <Texture class="About__texture1" />
    <Texture class="About__texture2" />
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
  text-align: center;
  color: $black-2;
  background-color: rgba($red-4, 0.8);
  position: relative;
  height: 700px;

  .About__heading {
    padding-top: 80px;
  }

  .About__main {
    display: flex;
    justify-content: center;
    width: 100%;

    p {
      max-width: 50%;
    }
  }

  .About__texture1 {
    height: 330px;
    width: auto;
    position: absolute;
    right: 0;
    top: 100px;
  }

  .About__texture2 {
    height: 330px;
    width: auto;
    position: absolute;
    left: 0;
    top: 200px;
  }
}
</style>
