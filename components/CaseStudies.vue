<template>
  <section class="grid grid-cols-1 gap-4 md:py-8 md:grid-cols-2">
    <CaseStudie v-for="(study, index) in studies" :key="index" :study="study" />
  </section>
</template>

<script>
import CaseStudie from './CaseStudie.vue'
export default {
  name: 'CaseStudies',
  components: {
    CaseStudie,
  },
  data: () => {
    return {
      studies: [
        {
          link: 'content-marketing',
          image: '/case-study/1.png',
        },
        {
          link: 'content-marketing',
          image: '/case-study/2.png',
        },
        {
          link: 'content-marketing',
          image: '/case-study/3.png',
        },
        {
          link: 'content-marketing',
          image: '/case-study/4.png',
        },
      ],
    }
  },
}
</script>
