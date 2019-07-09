<template>
<div class="hello">
  <b-navbar navbar-light bg-light toggleable="md" fixed="top">
    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
    <b-collapse is-nav id="nav_collapse">
      <b-navbar-nav class="w-100">
        <b-navbar-nav align="right">
          <b-nav-item class="mr-md-5" to="/"><strong>Home</strong></b-nav-item>
          <b-nav-item class="mr-md-5" to="/about"><strong>About</strong></b-nav-item>
          <b-nav-item class="mr-md-5" to="/info#section8"><strong>Info</strong></b-nav-item>
        </b-navbar-nav>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
  <div>
    <router-view></router-view>
  </div>
</div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div.info {
  margin-top: 160px;
  /* border: 1px solid black; */
}
</style>
