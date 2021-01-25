<template>
  <nav class="container">
    <div class="nav-content">
      <a href="#">
        <img src="img/logo.png" alt="logo" />
      </a>

      <ul class="nav-links">
        <li class="nav-link">
          <a href="#">Kort forklart</a>
        </li>
        <li class="nav-link">
          <a href="#">Var App</a>
        </li>
        <li class="nav-link">
          <a href="#">Del-Eie</a>
        </li>
        <li class="nav-link">
          <a href="#">Forvaltning</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style lang="scss">
.nav-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 48px 0 35px;
  
  .nav-links {
    list-style: none;
  }

  .nav-link {
    display: inline-block;
    margin: 0 27px;

    a {
      font-size: 24px;
      font-weight: bold;
      text-decoration: none;
      color: #1c9d88;
      transition: 0.3s;
    }

    a:hover {
      color: grey;
    }
  }
}
</style>