<template>
  <section class="container">
    <h3
      class="text-2xl md:text-3xl text-gray-300 uppercase font-bold mt-10 md:mt-20"
    >
      <strong>Case studies</strong>
    </h3>
    <div class="grid grid-cols-1 gap-8 md:py-8 md:grid-cols-2 mt-5 md:mt-0">
      <CaseStudie
        v-for="(study, index) in studies"
        :key="index"
        :study="study"
      />
    </div>
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
