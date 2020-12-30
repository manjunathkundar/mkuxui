<template>
  <nuxt-link :to="link">
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
  computed: {
    link() {
      return ('/case-study/' + this.study.link).replace('//', '/')
    },
  },
}
</script>
