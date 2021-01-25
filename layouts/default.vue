<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.container {
  max-width: 100%;
  margin: 0 auto;
}

@media only screen and (min-width: 576px) {
  .container {
    max-width: 540px;
  }
}

@media only screen and (min-width: 768px) {
  .container {
    max-width: 720px;
  }
}

@media only screen and (min-width: 992px) {
  .container {
    max-width: 960px;
  }
}

@media only screen and (min-width: 1200px) {
  .container {
    max-width: 1140px;
  }
}

@media only screen and (min-width: 1440px) {
  .container {
    max-width: 1320px;
  }
}

.green-btn,
.black-btn {
  display: inline-block;
  padding: 16px 60px;
  border-radius: 16px;
  font-size: 30px;
  font-weight: 500;
  text-decoration: none;
  transition: 0.4s;
}

.green-btn {
  color: white;
  background-color: #1d9d88;
}

.green-btn:hover {
  color: white;
  background-color: grey;
}

.black-btn {
  color: white;
  background-color: #233835;
}

.black-btn:hover {
  background-color: grey;
}
</style>
