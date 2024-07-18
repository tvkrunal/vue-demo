<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#nav-collapse" aria-controls="nav-collapse" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="nav-collapse">
      <ul class="navbar-nav mr-auto text-left">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Register</a>
        </li>
      </ul>
      <!-- <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      </form> -->
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<style scoped>
/* You can add custom styles here */
</style>
