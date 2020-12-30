<template>
  <nuxt-link :to="study.link">
    <img :src="study.image" :alt="study.name" />
  </nuxt-link>
</template>

<script>
export default {
  name: 'CaseStudy',
  props: {
    study: {
      type: Object,
      default: () => {},
    },
  },
}
</script>
