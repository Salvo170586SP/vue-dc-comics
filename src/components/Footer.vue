<template>
  <footer>
    <div class="top-footer">
      <div class="container">
          <div class="box-nav">
        <div class="nav-left">
          <nav>
            <h4>DC COMICS</h4>
            <ul>
              <li><a href="#">Chataraters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">Tv</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Video</a></li>
              <li><a href="#">News</a></li>
            </ul>

            <h4>SHOP</h4>
            <ul>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </nav>
        </div>
        <div class="nav-center">
          <nav>
            <h4>DC</h4>
            <ul>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy policy(New)</a></li>
              <li><a href="#">Ad Choise</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Crtificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
          </nav>
        </div>

        <div class="nav-right">
          <nav>
            <h4>SITES</h4>
            <ul>
              <li><a href="#">Dc</a></li>
              <li><a href="#">Mad Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">Dc Universe</a></li>
              <li><a href="#">Dc Power Visa</a></li>
            </ul>
          </nav>
        </div>
      </div>
      </div>
    </div>
    <div class="bottom-footer"></div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>

.box-nav{
    padding-top: 20px;
}

.nav-left,
.nav-center,
.nav-right {
  display: inline-block;
  margin-left: 50px;
}

.top-footer {
  min-height: 400px;
  background-image: url("../assets/img/footer-bg.jpg");
  color: white;
}

ul li {
  list-style-type: none;
  margin-top: ;
}

ul li a {
  color: white;
  font-size: 0.8rem;
  font-weight: 100;
}
</style>