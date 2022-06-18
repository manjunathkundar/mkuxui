<template>
  <section>
    <div
      class="container mt-8 flex flex-col-reverse items-center justify-between py-4 md:py-8 md:flex-row"
    >
      <div>
        <h1 class="text-4xl mt-10 md:m-0">
          Hi. I’m <strong>Manjunath Shankar.</strong>
        </h1>
        <p class="mt-2 text-gray-500">You can call me Manju 🙂</p>
        <p class="text-3xl mt-4 pr-6">
          I <strong>lead</strong> and <strong>design</strong> products that
          people love. I enjoy creating user-centric, delightful, and human
          experiences.
        </p>
        <p class="mt-6 md:mt-8">
          <a
            href="/case-study/Manjunath-shankar-CV.pdf"
            target="_blank"
            class="inline-block w-full px-8 py-2 text-lg font-bold text-center border-2 md:text-left md:w-auto border-pink text-pink rounded-full hover:bg-pink hover:text-white transition ease-in-out delay-100 hover:-translate-y-1 hover:scale-105"
            >Download my CV</a
          >
        </p>

        <!-- <h5 class="mt-4 lg:mt-8">
        Former Design Lead at
        <a
          href="https://www.manipaltechnologies.com/"
          target="_blank"
          class="text-pink"
          >Manipal Technologies</a
        >
      </h5> -->
      </div>
      <img
        src="/manjunath.png"
        alt="Manjunath"
        class="max-w-fit rounded profile"
      />
    </div>
    <div class="bg-gray py-10 mt-5 md:mt-0">
      <div class="container">
        <p class="text-lg">
          I’m currently designing product for
          <a
            href="https://www.tangible.store/"
            class="text-pink hover:underline"
            target="_blank"
            ><strong>Tangible</strong>
          </a>
          - LA, USA <span class="text-xs">(Remote).</span> Previously Product
          Designer at
          <a
            href="https://www.dragapp.com/"
            class="text-pink hover:underline"
            target="_blank"
            ><strong>Drag</strong>
          </a>
          - UK <span class="text-xs">(Remote).</span>
        </p>
      </div>
    </div>
    <div class="container mt-10 md:mt-20">
      <h3 class="text-2xl md:text-3xl text-gray-300 uppercase font-bold mb-10">
        <strong>My recent products</strong>
      </h3>
      <div class="flex space-x-12 md:space-x-20">
        <a href="https://www.tangible.store/" target="_blank">
          <img
            class="max-w-fit"
            src="/tangible-logo.png"
            alt="Tangible store"
          />
        </a>
        <a href="https://www.dragapp.com/" target="_blank">
          <img class="max-w-fit" src="/drag-logo.png" alt="Tangible store" />
        </a>
        <a href="https://emerhub.com/" target="_blank">
          <img class="max-w-fit" src="/emerhub-logo.png" alt="Tangible store" />
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Feature',
}
</script>

<style>
@media (min-width: 768px) {
  .text-4xl {
    font-size: 2.6rem;
  }
  .text-3xl {
    font-size: 2rem;
    line-height: 3rem;
  }
}

/* .profile {
  box-shadow: 12px 13px #d61f69;
} */
</style>
