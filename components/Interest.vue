<template>
  <div class="container">
    <div class="interest-content">
      <h2 class="title">Boligfondet Del-Eie</h2>
      <h3 class="subtitle">Din vei inn pa boligmarkedet?</h3>

      <div class="main">
        <img src="img/interest.png" alt="interest" />

        <div class="text">
          <p class="primary">Kjop det du har rad til og lei resten av Boligfondet.</p>

          <p class="secondary">- Bo hvor du vil, lkke bare der du har rad</p>

          <p class="secondary">- Redusert leiekostnad (Eier du 60% leier du bare 40%)</p>

          <p class="secondary">- Del i verdiutviklingen (60% eierskap = 60% verdiutvikling)</p>
        </div>
      </div>

      <div class="bottom">
        <p>
          ?Interessert i Del-Eie
          <br />Legg din mail, sa tar vi kontakt
        </p>

        <a class="green-btn" href="#">Send meg en email</a>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.interest-content {
  padding: 146px 0 152px;
  font-size: 30px;
  color: #233835;

  .title {
    font-size: 50px;
    font-weight: 600;
    text-align: center;
  }

  .subtitle {
    font-size: 42px;
    font-weight: 600;
    text-align: center;
    color: #1d9d88;
  }

  .main {
    display: flex;
    justify-content: center;
    margin: 88px 0 96px;

    img {
      object-fit: contain;
    }

    .text {
      margin-left: 80px;

      .primary {
        margin-top: 58px;
        font-weight: bold;
      }

      .secondary {
        margin-top: 40px;
      }
    }
  }

  .bottom {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: auto;

    p {
      margin-right: 50px;
      direction: rtl;
    }
  }
}
</style>