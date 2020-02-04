<template>
  <main>
    <header>
      <logo />
      <div class="container">
        <div class="text">
          <h2>Marlon Felix</h2>
          <p>Oi, meu nome é Marlon Felix, nasci em Montes Claros/MG e atualmente faço parte do time de desenvolvimento da Vigia de Preço, trabalho remoto, amo viajar e trocar novas experiências.</p>
        </div>
      </div>
    </header>
    <section class="skills">
      <div class="container">
        <h2>Habilidades</h2>
        <ul>
          <li>HTML e Template Languages</li>
          <li>CSS (SASS, LESS, Stylus) <span>my expertise</span></li>
          <li>Design Responsivo (Mobile first)</li>
          <li>Javascript (ES6)</li>
          <li>Vue js, React, React Native</li>
          <li>Design UI UX</li>
          <li>GIT</li>
          <li>Scrum</li>
          <li>...</li>
        </ul>
      </div>
    </section>
    <section class="contact">
      <div class="container">
        <h2>Contato</h2>
        <Social />
      </div>
    </section>
  </main>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Social from '~/components/Social.vue'

export default {
  head: {
    title: 'Marlon Felix - Frontend develop'
  },
  components: {
    Logo,
    Social
  }
}
</script>
<style lang="scss">
  header {
    height: 100vh;
    padding: 20px;
    .container {
      height: 100%;
      display: flex;
      align-items: center;
    }
    .text {
      max-width: 580px;
    }
  }
  .skills, .contact {
    height: 100vh;
    padding: 40px 0;
    display: flex;
    align-items: center;
    h2 {
      font-size: 36px;
      margin-bottom: 90px;
    }
  }
  .skills {
    ul {
      li {
        margin-bottom: 20px;
        span {
          color: #00E987;
        }
      }
    }
  }
  .contact {
    .social {
      display: flex;
      justify-content: center;
      a {
        margin: 0 50px;
      }
    }
  }
</style>
