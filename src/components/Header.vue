<template>
 <nav class="navbar navbar-expand-lg navbar-dark bg-black">
    <div class="container">
      <router-link to="/">NakRide</router-link>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-expanded="false">
              How it works
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Owner</a></li>
              <li><a class="dropdown-item" href="#">Customer</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">FAQ</a></li>
            </ul>
          </li>
          <li class="nav-item">
             <router-link to="/about">Contact Us</router-link> |
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-expanded="false">
              Login
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Customer</a></li>
              <li><a class="dropdown-item" href="#">Owner</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-expanded="false">
             Register
           </a>
           <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Customer</a></li>
            <li><a class="dropdown-item" href="#">Owner</a></li>
          </ul>
        </li>

      </ul>

    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bg-black {
    background-color: black;
  }

</style>
