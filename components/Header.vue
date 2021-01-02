<template>
  <div class="Header">
    <b-navbar toggleable="lg" class="Header__nav">
      <b-navbar-brand href="#">
        <img class="Header__logo" src="~assets/img/Logo.png" />
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="Header__links ml-auto">
          <b-nav-item href="#">Work</b-nav-item>
          <b-nav-item href="#">About</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.Header {
  height: auto;
  width: 100%;

  .Header__logo {
    width: 140px;
  }

  .Header__nav {
    background-color: white;
  }

  .Header__links {
    display: grid;
    grid-template-rows: 1fr;
    grid-template-columns: repeat(3, 1fr);
    grid-column-gap: 60px;
  }
}
</style>
