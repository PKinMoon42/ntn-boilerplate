<template>
  <div class="main text-center flex flex-col items-center justify-center">
    <!-- <logo /> -->
    <h1 class="title">Nuxt — Tailwind — Netlify CMS</h1>
    <h2 class="subtitle">Boilerplate</h2>
    <div class="elfsight-app-8cc89f13-2f97-4714-b2da-7737a9927a5f"></div>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  // components: {
  //   Logo
  // },
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }]
    }
  }
}
</script>
