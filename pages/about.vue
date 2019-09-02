<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="Who Are We?"
      subtitle
      image="/uploads/about-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          <h3>Who are we?</h3>

          <p>Like you, we are real people running a real business.</p>
          <p>We get tired. We get stressed. We’re human.</p>
          <p>
            Because we’re people just like you, we’re capable of understanding
            you and the needs of your business.
          </p>
          <p>
            We’re not some behemoth marketing firm that makes outlandish
            promises shortly before taking your hard earned money and delivering
            next to nothing.
          </p>
          <p>We don’t promise things we can’t deliver.</p>
          <p>We don’t compromise our values.</p>
          <p>And we don’t work with assholes.</p>
          <p>
            We have a passion for helping people like us. People with drive,
            ambition, and a passion for what they do.
          </p>
          <p>
            If you’re interested in a partner that will speak to you honestly,
            be committed for the long haul, and invest in your success than
            you’ve come to the right place.
          </p>
          <p>
            Reach out to us with any questions you have or fill out our intake
            form and we’ll be in touch.
          </p>
        </div>
      </template>

      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: `About | ${this.$siteConfig.siteName}`
    }
  }
}
</script>
