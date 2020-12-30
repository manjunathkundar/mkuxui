<template>
  <div :class="[isCaseStudyPage ? 'bg-green' : 'bg-white']">
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
export default {
  name: 'Default',
  data: () => {
    return {
      isCaseStudyPage: false,
    }
  },
  watch: {
    $route() {
      this.isCaseStudyPage =
        this.$nuxt.$route.path.split('/')[1].trim() === 'case-study'
    },
  },
  mounted() {
    this.isCaseStudyPage =
      this.$nuxt.$route.path.split('/')[1].trim() === 'case-study'
  },
}
</script>

<style>
html,
body {
  font-family: 'Nunito', sans-serif;
  @apply text-black;
}

.container {
  max-width: 950px;
  @apply px-6 w-full;
}

@media (min-width: 1024px) {
  .container {
    @apply px-0;
  }
}
</style>
