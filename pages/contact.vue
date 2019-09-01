<template>
  <div id="contact-page" class="page-wrapper contact-page content-page">
    <site-hero
      title="Have a Question?"
      subtitle="We'll get back to you as soon as possible"
      image="/uploads/contact-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <!-- <div class="tile is-ancestor"> -->
        <div class="is-8">
          <article class="tile is-child box">
            <contact-form />
          </article>
        </div>
        <!-- </div> -->
      </template>
      <template v-slot:sidebar>
        <h3 class="subtitle is-4">Latest Posts</h3>
        <!-- Latest Posts -->
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
<script>
import ContactForm from '~/components/ContactForm'
export default {
  head() {
    return {
      title: `Contact | ${this.$siteConfig.siteName}`
    }
  },
  components: { ContactForm }
}
</script>
