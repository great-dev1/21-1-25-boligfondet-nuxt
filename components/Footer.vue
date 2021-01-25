<template>
  <footer>
    <div class="container">
      <div class="footer-content">
        <div class="left">
          <img src="img/logo-icon-white.png" alt="logo" />

          <div class="mid">
            <a href="#">Privacry Policy</a>
            <br />
            <a href="#">Terms of Use</a>
          </div>

          <div>
            <b>Contact us:</b>
            <br />
            <a href="#">info@boligfondet.no</a>
          </div>
        </div>

        <div class="right">
          <a href="#">
            <img src="img/instagram-icon.png" alt="instagram" />
          </a>

          <a href="#">
            <img src="img/twitter-icon.png" alt="twitter" />
          </a>

          <a href="#">
            <img src="img/facebook-icon.png" alt="facebook" />
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
footer {
  padding: 72px 0;
  color: white;
  background-color: #233835;

  .footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;

    .left {
      display: flex;
      align-items: center;

      .mid {
        margin-left: 40px;
        margin-right: 60px;
      }

      a {
        text-decoration: none;
        color: white;
        transition: 0.3s;
      }

      a:hover {
        color: grey;
      }
      
    }

    .right {
      a {
        margin: 0 12px;
      }
    }
  }
}
</style>