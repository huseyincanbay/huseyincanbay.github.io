<template>
  <footer class="bg-white py-8 md:py-4" id="contact">
    <div class="container mx-auto px-4 md:px-8 p-8">
      <p class="text-1xl text-center text-gray-900 mt-4 md:mt-0">
        Created by <strong>Hüseyin Canbay</strong> &copy; 2023
      </p>
    </div>
    <div
      v-if="showGoUpArrow"
      class="flex justify-center items-center bg-gray-500 text-white w-12 h-12 fixed bottom-4 right-4 rounded-full cursor-pointer"
      @click="goToTop"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="currentColor"
        class="w-6 h-6"
        viewBox="0 0 24 24"
      >
        <path d="M7.41 15.41L12 10.83l4.59 4.58L18 14l-6-6-6 6z" />
      </svg>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      showGoUpArrow: false,
    };
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.handleScroll);
  },
  methods: {
    goToTop() {
      window.scrollTo({ top: 0, behavior: "smooth" });
    },
    handleScroll() {
      this.showGoUpArrow = window.scrollY > 0;
    },
  },
};
</script>

<style scoped>
/* Add your custom styles here if needed */
</style>
