<template>
  <div class="logo-wrapper">
    <div
      :class="{
        'logo-inner': true
      }"
    >
      <img src="../assets/uploads/site-logo.svg" />
    </div>
  </div>
</template>
<script>
export default {
  name: 'SiteLogo',
  data() {
    return {
      frames: 5,
      currentFrame: 1,
      blinking: true
    }
  }
}
</script>
