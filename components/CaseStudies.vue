<template>
  <section class="mt-16 grid grid-cols-1 gap-8 md:py-8 md:grid-cols-2">
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
          link: 'incorporation',
          image: '/case-study/inc-thumb.png',
        },
        {
          link: 'payroll',
          image: '/case-study/pay-thumb.png',
        },
        {
          link: 'diet-tracker',
          image: '/case-study/diet-thumb.png',
        },
        {
          link: 'rightpoi',
          image: '/case-study/rightpoi-thumb.png',
        },
        {
          link: 'logo-designs',
          image: '/case-study/mk-thumb.png',
        },
      ],
    }
  },
}
</script>
