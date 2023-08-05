<template>
  <section class="bg-gray-900 text-white" id="hero">
    <div
      class="mx-auto max-w-screen-xl px-4 py-32 lg:flex lg:h-screen lg:items-center"
    >
      <div class="lg:flex lg:justify-start lg:items-center lg:w-3/4">
        <div class="mx-auto max-w-3xl text-center">
          <h1
            class="bg-gradient-to-r from-green-300 via-blue-500 to-purple-600 bg-clip-text text-3xl font-extrabold text-transparent sm:text-5xl pb-1"
          >
            Hello!
            <span class="sm:block">I am Hüseyin Canbay</span>
          </h1>

          <p class="mx-auto mt-5 max-w-xl sm:text-xl/relaxed">
            Türkiye based Software Engineer passionate about Full Stack
            Development.
          </p>
          <div class="flex justify-center items-center mt-6">
            <ul class="flex space-x-4 gap-8">
              <li>
                <a
                  class="text-white text-xl mr-2 hover:text-indigo-500"
                  href="mailto:huseyincanbay10@gmail.com"
                  target="_blank"
                >
                  <i class="fas fa-envelope fa-lg"></i>
                </a>
              </li>
              <li>
                <a
                  class="text-white text-xl mr-2 hover:text-indigo-500"
                  href="https://www.linkedin.com/in/huseyincanbay10/"
                  target="_blank"
                >
                  <i class="fab fa-linkedin fa-lg"></i>
                </a>
              </li>
              <li>
                <a
                  class="text-white text-xl mr-2 hover:text-indigo-500"
                  href="https://github.com/huseyincanbay"
                  target="_blank"
                >
                  <i class="fab fa-github fa-lg"></i>
                </a>
              </li>
            </ul>
          </div>

          <div class="img mt-8 flex flex-wrap justify-center gap-4">
            <a
              class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl hover:from-purple-500 hover:to-blue-400 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-8 py-2.5 text-center mr-2 mb-2"
              href="https://huseyincanbay.github.io/src/assets/huseyin-canbay-cv.pdf"
              download="huseyin-canbay-cv.pdf"
              target="_blank"
            >
              <button type="button">Download CV</button>
            </a>
          </div>
        </div>
      </div>

      <div class="img lg:flex lg:justify-end lg:items-center lg:w-2/4 mt-2">
        <img
          src="/src/assets/undraw_programming_re_kg9v.svg"
          alt="Hero Image"
          class="w-96 h-96"
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
.img {
  transition: transform 0.5s;
}

.img:hover {
  transform: translateY(-8px);
}
</style>
