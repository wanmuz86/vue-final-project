<template>
 <footer class="bg-black py-3">
      <div class="container">
        <div class="row text-light">
          <div class="col-3"><h5>Get started</h5>
            <ul class="list-unstyled">
              <li><a href="#">Owner Guidelines</a></li>
              <li><a href="#">Customer Guidelines</a></li>
              <li><a href="#">Frequently Asked Questions (FAQ)</a></li>
            </ul>
          </div>
          <div class="col-3">
            <h5>Policies</h5>
            <ul class="list-unstyled">
              <li><a href="#">Terms and Conditions</a></li>
            </ul>

          </div>
          <div class="col-3"><h5>Popular Areas</h5>
          <ul class="list-unstyled">
              <li><a href="#">Kuala Lumpur</a></li>
              <li><a href="#">Ipoh</a></li>
              <li><a href="#">Georgetown</a></li>
            </ul></div>
          <div class="col-3"><h5>Social Media</h5>
          <ul class="list-inline">
            <li class="list-inline-item"><i class="fab fa-facebook"></i></li>
            <li class="list-inline-item"><i class="fab fa-instagram"></i></li>
            <li class="list-inline-item"><i class="fab fa-twitter-square"></i></li>

          </ul>
          </div>
        </div>
        <div class="row py-3 text-light">
          &copy; 2020  Terminal Bersepadu Selatan, Bandar Tasek Selatan, Kuala Lumpur.
        </div>
      </div>

    </footer>
</template>

<script>
export default {
  name: 'Footer',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  footer ul li a {
    color:white;
    text-decoration: none;
  }
  footer ul li i {
    font-size: 30px;
  }
  .bg-black {
    background-color: black;
  }
</style>
