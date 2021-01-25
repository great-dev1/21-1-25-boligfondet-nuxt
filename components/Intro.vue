<template>
  <div class="container">
    <div class="intro-content">
      <h2 class="title">
        Du eier selskapet som eier
        <br />utleie eiendommen
      </h2>

      <div class="main">
        <div class="left">
          <p class="detail first">
            Du vil bli eiendomsinvestor ved a investere i Boligfondet
          </p>

          <p class="detail second">
            Du vil bli eiendomsinvestor ved a investere i Boligfondet
          </p>

          <p class="detail third">
            Du vil bli eiendomsinvestor ved a investere i Boligfondet
          </p>
        </div>

        <div>
          <img src="img/intro.png" alt="intro" />
        </div>

        <div class="right">
          <p class="detail first">
            Du vil bli eiendomsinvestor ved a investere i Boligfondet
          </p>

          <p class="detail second">
            Du vil bli eiendomsinvestor ved a investere i Boligfondet
          </p>

          <p class="detail third">
            Du vil bli eiendomsinvestor ved a investere i Boligfondet
          </p>
        </div>
      </div>

      <h2 class="title">
        Du eier selskapet som eier
        <br />utleie eiendommen
      </h2>
    </div>
  </div>
</template>

<style lang="scss">
.intro-content {
  padding: 88px 0 152px;
  color: #233835;

  .title {
    font-size: 42px;
    font-weight: 600;
    line-height: 1.3;
    text-align: center;
  }

  .main {
    display: flex;
    justify-content: space-between;
    margin: 44px 0;

    .left, .right {
      display: flex;
      flex-direction: column;

      .first {
        margin-top: 66px;
      }

      .second {
        margin: 150px 0 192px;
      }
    }

    .right {
      direction: rtl;
    }

    .detail {
      font-size: 30px;
      line-height: 1.1;
    }
  }
}
</style>