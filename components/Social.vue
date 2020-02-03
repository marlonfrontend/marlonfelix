<template>
  <div class="social">
    <a href="#">
      <img src="~/assets/images/github.svg" alt="">
    </a>
    <a href="#">
      <img src="~/assets/images/linkedin.svg" alt="">
    </a>
    <a href="#">
      <img src="~/assets/images/mail.svg" alt="">
    </a>
  </div>
</template>

<script>
export default {
  name: 'Social'
}
</script>
<style lang="scss" scoped>
  .social {
    display: flex;
    justify-content: center;
    a {
      margin: 0 50px;
    }
  }
</style>
