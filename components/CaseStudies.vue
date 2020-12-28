<template>
  <section class="grid grid-cols-2 gap-4 py-8">
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
          name: 'Content Marketing',
          link: '#',
          image: '/case-study/1.png',
          background: 'dark',
        },
        {
          name: 'Content Marketing',
          link: '#',
          image: '/case-study/2.png',
          background: 'light',
        },
        {
          name: 'Content Marketing',
          link: '#',
          image: '/case-study/3.png',
          background: 'light',
        },
        {
          name: 'Content Marketing',
          link: '#',
          image: '/case-study/4.png',
          background: 'light',
        },
      ],
    }
  },
}
</script>
