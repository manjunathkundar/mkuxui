<template>
  <div>
    <footer
      class="flex flex-col items-center justify-around h-64 mt-8 text-center border-t border-gray-300"
    >
      <div id="contact-section">
        <div class="text-xl font-bold">Let's Connect!</div>
        <div class="mt-2">
          <span class="inline-block"
            >Feel free to reach out for collaborations or just a friendly hello
            🙂</span
          >
        </div>
        <div class="mt-2">
          <a
            href="mailto:manjunathmds@gmail.com"
            class="font-bold text-pink hover:underline"
            >manjunathmds@gmail.com</a
          >
        </div>

        <div class="flex items-center justify-center mt-6 space-x-6">
          <a
            href="https://in.linkedin.com/in/manjunath-kunder-47316383"
            target="_blank"
          >
            <img src="/linkedin.png" alt="" />
          </a>
          <!-- <a href="https://www.behance.net/manjunathkunder" target="_blank">
            <img src="/behance.png" alt="" />
          </a> -->
          <a href="https://dribbble.com/mkuxui" target="_blank" class="ml-12">
            <img src="/dribble.png" alt="" />
          </a>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>
