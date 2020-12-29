<template>
  <div>
    <button class="lg:hidden" @click="toggleMenu">
      <svg
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M13 18H20M4 6H20H4ZM4 12H20H4Z"
          stroke="#1A202E"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
    </button>
    <ul class="items-center hidden -ml-8 uppercase lg:flex">
      <li v-for="link in links" :key="link.name">
        <nuxt-link class="ml-8 hover:text-pink" :to="link.to">
          {{ link.name }}
        </nuxt-link>
      </li>
    </ul>

    <div
      v-show="showMenu"
      class="fixed top-0 bottom-0 left-0 right-0 z-50 bg-white lg:hidden"
      style="opacity: 90%"
    >
      <button class="absolute top-0 right-0 mt-6 mr-6" @click="toggleMenu">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
          class="feather feather-x"
        >
          <line x1="18" y1="6" x2="6" y2="18"></line>
          <line x1="6" y1="6" x2="18" y2="18"></line>
        </svg>
      </button>

      <div class="flex items-center justify-center w-full h-screen">
        <ul class="flex flex-col items-center my-auto text-lg uppercase">
          <li
            v-for="link in links"
            :key="link.name"
            class="my-4"
            @click="toggleMenu"
          >
            <nuxt-link class="hover:text-pink" :to="link.to">
              {{ link.name }}
            </nuxt-link>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => {
    return {
      showMenu: false,
      links: [
        { name: 'Home', to: '/' },
        { name: 'About', to: '/about' },
        { name: 'Contact', to: '/contact' },
      ],
    }
  },
  methods: {
    toggleMenu() {
      this.showMenu = !this.showMenu
    },
  },
}
</script>
