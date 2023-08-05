<template>
  <nav
    class="bg-white dark:bg-gray-900 fixed w-full z-20 top-0 left-0 border-b border-gray-200 dark:border-gray-600"
  >
    <div
      class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
    >
      <a href="/" class="flex items-center">
        <span
          class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white bg-gradient-to-br from-indigo-600 to-blue-900 bg-clip-text text-transparent"
        >
          |Canbay|
        </span>
      </a>
      <div class="flex md:order-2">
        <a
          href="mailto:huseyincanbay10@gmail.com"
          target="_blank"
          rel="noopener noreferrer"
          class="text-white bg-gradient-to-br from-indigo-600 via-purple-500 to-blue-700 hover:from-indigo-700 hover:via-purple-700 hover:to-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 ml-24 text-center md:mr-0 dark:bg-gradient-to-br dark:from-indigo-800 dark:via-purple-800 dark:to-blue-600 dark:hover:from-indigo-900 dark:hover:via-purple-900 dark:hover:to-blue-700 dark:focus:ring-blue-800"
        >
          Hire Me!
        </a>
      </div>
      <button
        @click="toggleMenu"
        class="md:hidden flex items-center px-3 py-2 text-blue-600 dark:text-white"
      >
        <svg
          class="w-6 h-6"
          fill="none"
          stroke="currentColor"
          viewBox="0 0 24 24"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16m-7 6h7"
          ></path>
        </svg>
      </button>
      <!-- Mobile -->
      <div
        v-if="showMenu"
        class="md:hidden absolute top-full w-full bg-white dark:bg-gray-800 border-b border-gray-200 dark:border-gray-700"
      >
        <ul class="px-4 py-2">
          <li>
            <a
              href="#hero"
              class="block py-2 text-blue-700 font-medium dark:text-blue-500"
              aria-current="page"
              @click="toggleMenu"
              >Home</a
            >
          </li>
          <li>
            <a
              href="#about"
              class="block py-2 text-gray-900 rounded hover:bg-gray-100 dark:text-white dark:hover:text-blue-500"
              @click="toggleMenu"
              >About</a
            >
          </li>
          <li>
            <a
              href="#skills"
              class="block py-2 text-gray-900 rounded hover:bg-gray-100 dark:text-white dark:hover:text-blue-500"
              @click="toggleMenu"
              >Skills & Tools</a
            >
          </li>
          <li>
            <a
              href="#projects"
              class="block py-2 text-gray-900 rounded hover:bg-gray-100 dark:text-white dark:hover:text-blue-500"
              @click="toggleMenu"
              >Projects</a
            >
          </li>
          <li>
            <a
              href="#experiences"
              class="block py-2 text-gray-900 rounded hover:bg-gray-100 dark:text-white dark:hover:text-blue-500"
              @click="toggleMenu"
              >Experiences</a
            >
          </li>
        </ul>
      </div>
      <!-- Desktop -->
      <div
        class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1"
        id="navbar-sticky"
      >
        <ul
          class="flex flex-col p-4 md:p-0 mt-4 font-medium border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700"
        >
          <li>
            <a
              href="#hero"
              class="block py-2 pl-3 pr-4 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-blue-500"
              aria-current="page"
              >Home</a
            >
          </li>
          <li>
            <a
              href="#about"
              class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
              >About</a
            >
          </li>
          <li>
            <a
              href="#skills"
              class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
              >Skills & Tools</a
            >
          </li>
          <li>
            <a
              href="#projects"
              class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
              >Projects</a
            >
          </li>
          <li>
            <a
              href="#experiences"
              class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
              >Experiences</a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      showMenu: false,
    };
  },
  methods: {
    toggleMenu() {
      this.showMenu = !this.showMenu;
    },
  },
};
</script>
