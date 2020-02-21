<template>
  <section>
    <h1 class="title">Faschingsumzug Kirchberg/We</h1>
    <img
      src="https://res.cloudinary.com/dkaq2njxs/image/upload/v1582297238/IMG-20200221-WA0001_t6v7eh.jpg"
    >
    <footer>
      Website Proudly presented by
      <a href="https://www.macherjek.at">macherjek.at</a>
    </footer>
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";
import IconLink from "~/components/IconLink.vue";

export default {
  components: {
    Logo,
    IconLink
  }
};
</script>

<style scoped>
section {
  max-width: 600px;
}

a {
  color: #1E71B8;
  font-weight: bold;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 400;
  color: #2E495E;
  letter-spacing: 1px;
  font-size: 2em;
  margin-bottom: 2rem;
}

img {
  margin: 0 auto;
  max-width: 100%;
  display: block;
  min-width: 370px;
}
footer {
  padding-top: 2rem;
}
</style>
