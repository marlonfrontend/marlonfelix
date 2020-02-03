<template>
  <div>
    <nuxt />
  </div>
</template>

<style lang="scss">
html {
  font-family: 'Nunito', sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
body {
  background-color: #111;
  color: #fff;
}
p {
  letter-spacing: .07rem;
  line-height: 2.1rem;
}
h2 {
  font-family: 'Overpass', sans-serif;
  margin-bottom: 20px;
  font-weight: 500;
}
/* scrollbar */
::-webkit-scrollbar-track {
  background-color: #333;
}
::-webkit-scrollbar {
  width: 6px;
  background-color: #f5f5f5;
}
::-webkit-scrollbar-thumb {
  background-color: rgb(242, 242, 242);
}

/* grid */
.container {
  max-width: 1140px;
  margin: 0 auto;
  width: 100%;
}
</style>
