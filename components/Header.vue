<template>
  <div class="container mx-auto">
    <header class="flex items-center justify-between h-20 text-xs font-bold">
      <nuxt-link to="/">
        <svg
          width="62"
          height="28"
          viewBox="0 0 62 28"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M16.828 28L21.5005 19.178L12.7885 0H4.32666L16.828 28Z"
            fill="url(#paint0_linear)"
          />
          <path
            d="M32.751 28L37.4236 19.178L28.7116 0H20.2498L32.751 28Z"
            fill="url(#paint1_linear)"
          />
          <path
            d="M8.65332 27.9984L4.67254 19.0812L0 27.9032"
            fill="url(#paint2_linear)"
          />
          <path
            d="M53.3467 0L57.3275 8.91717L62 0.0967705"
            fill="url(#paint3_linear)"
          />
          <path
            d="M45.1998 0L40.5273 8.82198L49.2393 28H57.7011L45.1998 0Z"
            fill="url(#paint4_linear)"
          />
          <defs>
            <linearGradient
              id="paint0_linear"
              x1="12.9136"
              y1="0"
              x2="12.9136"
              y2="28"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#D61F69" />
              <stop offset="1" stop-color="#751A3D" />
            </linearGradient>
            <linearGradient
              id="paint1_linear"
              x1="16.5"
              y1="1.33983e-07"
              x2="28.8367"
              y2="28"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#D61F69" />
              <stop offset="1" stop-color="#751A3D" />
            </linearGradient>
            <linearGradient
              id="paint2_linear"
              x1="4.32666"
              y1="19.0812"
              x2="4.32666"
              y2="27.9984"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#D61F69" />
              <stop offset="1" stop-color="#751A3D" />
            </linearGradient>
            <linearGradient
              id="paint3_linear"
              x1="57.6733"
              y1="0"
              x2="57.6733"
              y2="8.91717"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#D61F69" />
              <stop offset="1" stop-color="#751A3D" />
            </linearGradient>
            <linearGradient
              id="paint4_linear"
              x1="49.1142"
              y1="0"
              x2="49.1142"
              y2="28"
              gradientUnits="userSpaceOnUse"
            >
              <stop stop-color="#D61F69" />
              <stop offset="1" stop-color="#751A3D" />
            </linearGradient>
          </defs>
        </svg>
      </nuxt-link>
      <Menu />
    </header>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style>
.nuxt-link-exact-active {
  @apply text-pink;
}
</style>
