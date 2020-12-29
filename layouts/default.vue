<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<style>
html,
body {
  font-family: 'Nunito', sans-serif;
  @apply text-black;
}

.container {
  max-width: 950px;
  @apply px-6 w-full;
}

@media (min-width: 1024px) {
  .container {
    @apply px-0;
  }
}
</style>
