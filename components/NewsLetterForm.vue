<template>
  <div>
    <div class="has-text-centered">
      <a
        href="https://docs.google.com/forms/d/1EGi6MQ-vGU0H4Jhh9W37qDapJaeNmZSnvw_k4NJtl0U/viewform?edit_requested=true"
      >
        <button class="button is-primary">
          {{ $siteConfig.newsletter.btnText || 'Subscribe' }}
        </button>
      </a>
    </div>
  </div>
</template>

<style scoped>
a {
  text-decoration: none;
}
</style>
