<template>
  <div class="bottom-footer">
      <div class="container">
        <div class="b-footer">
          <div class="sign-up">
            <a href="#">SIGN-UP NOW!</a>
          </div>
          <div class="follow">
            <h3>FOLLOW US</h3>
            <div class="icon-social">
              <a href="#"
                ><img
                  src="../assets/img/footer-facebook.png"
                  alt="facebook logo"
              /></a>
              <a href="#"
                ><img src="../assets/img/footer-twitter.png" alt="twitter logo"
              /></a>
              <a href="#"
                ><img src="../assets/img/footer-youtube.png" alt="youtube logo"
              /></a>
              <a href="#"
                ><img
                  src="../assets/img/footer-pinterest.png"
                  alt="pintrest logo"
              /></a>
              <a href="#"
                ><img
                  src="../assets/img/footer-periscope.png"
                  alt="periscope logo"
              /></a>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: "FooterBottom",
}
</script>

<style lang="scss" scoped>

.bottom-footer{
   background-color: #303030;
}

.b-footer {
  display: flex;
  justify-content: space-around;
 }

.sign-up {
  padding: 20px 25px;
  border: 1px solid #0282f9;
  margin: 20px;
  a {
    color: white;
  }
}

.follow {
  display: flex;
  align-items: center;
  h3 {
    color: #0282f9;
  }
}

.icon-social {
  margin-left: 30px;
  img {
    margin-left: 10px;
  }
}
</style>