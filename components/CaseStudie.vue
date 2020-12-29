<template>
  <a href="#">
    <img :src="study.image" :alt="study.name" />
  </a>
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
