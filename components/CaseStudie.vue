<template>
  <a
    href="#"
    class="relative block text-4xl font-bold"
    :class="[study.background === 'dark' ? 'text-white' : 'text-black']"
  >
    <img :src="study.image" :alt="study.name" />
    <div class="absolute top-0 left-0 p-8">
      <h3 class="">{{ study.name }}</h3>

      <div class="flex mt-8 text-sm font-normal">
        Read Case Study
        <svg
          class="ml-2"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M21 12H3M17 8L21 12L17 8ZM21 12L17 16L21 12Z"
            :stroke="[study.background === 'dark' ? 'white' : '#1A202E']"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          />
        </svg>
      </div>
    </div>
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
