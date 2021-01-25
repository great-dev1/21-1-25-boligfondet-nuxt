<template>
  <div class="hero-container">
    <div class="left">
      <img src="img/hero.jpg" alt="hero" />
    </div>

    <div class="right">
      <div class="content">
        <h1 class="title">
          Alle kan bli
          <br />eiendomsinvestor
        </h1>

        <p class="detail">
          - Kjop utleie eiendom fra 10.000,-
          <br />- Manedlig overskudd utbbetalt til konto
          <br />- Boligfondet handterer utleiedriften
        </p>

        <a class="green-btn" href="#">Lag en profil</a>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.hero-container {
  display: flex;

  .left {
    width: 100%;

    img {
      max-width: 100%;
      height: 100%;
      object-fit: cover;
    }
  }

  .right {
    display: flex;
    align-items: center;
    width: 100%;
    background-color: #233835;

    .content {
      margin-top: 48px;
      margin-left: 70px;

      .title {
        font-size: 56px;
        line-height: 1.0;
        font-weight: 600;
        color: white;
      }

      .detail {
        margin: 32px 0 45px;
        font-size: 30px;
        line-height: 1.3;
        color: #1d9d88;
      }
    }
  }
}
</style>