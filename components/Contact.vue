<template>
  <div class="contact-container">
    <div class="main">
      <div class="container">
        <h2 class="title">Klar for a bli eiendomsinvestor?</h2>

        <p class="detail">
          Gi oss din email, sa sier vi til nar
          <br />appen lanseres
        </p>

        <div class="social-btn">
          <a href="#">
            <img src="img/google-btn.png" alt="google" />
          </a>
          <a href="#">
            <img src="img/appstore-btn.png" alt="appstore" />
          </a>
        </div>

        <a class="black-btn" href="#">Send meg en email</a>
      </div>
    </div>

    <img class="mobile-img" src="img/contact.png" alt="contact" />
  </div>
</template>

<style lang="scss">
.contact-container {
  position: relative;
  padding: 102px 0;

  .main {
    padding: 83px 0;
    background-color: #1d9d88;

    .title {
      font-size: 42px;
      font-weight: 600;
      line-height: 1.3;
      color: white;
    }

    .detail {
      margin: 10px 0 25px;
      font-size: 36px;
      line-height: 1.3;
      color: #233835;
    }

    .social-btn {
      margin-bottom: 18px;

      a {
        margin-right: 15px;
      }
    }
  }

  .mobile-img {
    position: absolute;
    top: 0;
    right: 24%;
  }
}
</style>