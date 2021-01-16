<template>
  <div>
    <div>
      <Header />
      <Nuxt />
    </div>
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
  line-height: 1.6;
  @apply text-black;
}

img,
video {
  width: 100%;
}

.container {
  max-width: 950px;
  @apply px-6 w-full mx-auto;
}

.large-container {
  max-width: 1440px;
  @apply w-full mx-auto;
}

.bullets li::before {
  content: '•';
  margin-right: 1em;
}

@media (min-width: 1024px) {
  .container {
    @apply px-0;
  }
}

.tns-nav {
  @apply -ml-1 flex justify-center mt-6;
}

.tns-nav button {
  @apply p-1 rounded-full bg-gray-500 ml-2;
}

.tns-nav .tns-nav-active {
  @apply bg-pink;
}

.tns-outer > button {
  @apply hidden;
}
</style>
