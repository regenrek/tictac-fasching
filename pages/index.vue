<template>
  <section>
    <div>
      <h1>Faschingsumzug Kirchberg/We
    </div>
    
    <img src="https://res.cloudinary.com/dkaq2njxs/image/upload/v1582297238/IMG-20200221-WA0001_t6v7eh.jpg" />

    <footer>
      Proudly presented by <a href="https://www.macherjek.at"></a>
    </footer>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
import IconLink from '~/components/IconLink.vue'

export default {
  components: {
    Logo,
    IconLink
  }
}
</script>

<style scoped>
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 400;
  font-size: 100px;
  color: #2E495E;
  letter-spacing: 1px;
  font-size: 6em;
}
.green {
  color: #00C48D;
}

.subtitle {
  font-weight: 300;
  font-size: 3em;
  color: #2E495E;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
