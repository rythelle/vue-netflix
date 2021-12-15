<template>
  <div>
    <b-navbar class="navbar" type="dark" variant="dark">
      <b-navbar-brand to="/">
        <img src="../assets/logo.png" class="d-inline-block align-top" alt="Kitten" height="30" />
      </b-navbar-brand>
      <b-navbar-nav>
        <b-nav-item to="/">Início</b-nav-item>
        <b-nav-item to="/series">Séries</b-nav-item>
        <b-nav-item to="/movies">Filmes</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
    <router-view />
  </div>
</template>

<script>
export default {};
</script>

<style>
.navbar {
  background: #141414 !important;
}
</style>
