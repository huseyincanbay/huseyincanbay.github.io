<template>
  <div class="container mx-auto py-20" id="projects">
    <h1 class="text-4xl text-center mb-8 mt-4">Projects</h1>
    <div class="mx-auto border-t-2 border-gray-900 w-44 mb-16"></div>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-12 p-5">
      <div class="flex">
        <div
          class="bg-gray-200 rounded-lg shadow-md p-4 flex flex-col justify-between transition duration-300 ease-in-out transform hover:scale-105"
        >
          <div>
            <img
              src="/src/assets/urlshortener.jpg"
              alt="URL Shortener"
              class="w-full mb-4 rounded-lg"
            />
            <h2 class="text-gray-800 text-xl font-bold mb-2">
              URL Shortener (Case Study)
            </h2>
            <p class="text-gray-800 text-sm mb-4">This application is a platform where users can shorten links. Users can create shortened links both without registration and with registration. They can also check various statistics on the dashboard.</p>
            <div class="mb-4">
              <span class="text-gray-800 text-sm font-semibold"
                >Used Tools:</span
              >
              <span class="text-gray-800 text-sm"> Vue.js, Firebase</span>
            </div>
          </div>
          <a
            href="https://github.com/huseyincanbay/vue-url-shortener"
            target="_blank"
            rel="noopener noreferrer"
            class="bg-gradient-to-r from-purple-500 via-indigo-500 to-purple-600 hover:from-purple-600 hover:to-blue-500 text-white py-2 px-4 mt-3 rounded-lg block text-center transition duration-300 ease-in-out transform hover:-translate-y-1 hover:scale-105"
          >
            View Project
          </a>
        </div>
      </div>
      <div class="flex">
        <div
          class="bg-gray-200 rounded-lg shadow-md p-4 flex flex-col justify-between transition duration-300 ease-in-out transform hover:scale-105"
        >
          <div>
            <img
              src="/src/assets/node.png"
              alt="Node Hotel API"
              class="w-full mb-4 rounded-lg"
            />
            <h2 class="text-gray-800 text-xl font-bold mb-2">
              Node Hotel API 
            </h2>
            <p class="text-gray-800 text-sm mb-4">This is a Hotel API project. Users can perform various CRUD operations based on Hotel Reservation concept.</p>
            <div class="mb-4">
              <span class="text-gray-800 text-sm font-semibold"
                >Used Tools:</span
              >
              <span class="text-gray-800 text-sm"> Node.js Express, MongoDB</span>
            </div>
          </div>
          <a
            href="https://github.com/huseyincanbay/node-hotel-api"
            target="_blank"
            rel="noopener noreferrer"
            class="bg-gradient-to-r from-purple-500 via-indigo-500 to-purple-600 hover:from-purple-600 hover:to-blue-500 text-white py-2 px-4 mt-3 rounded-lg block text-center transition duration-300 ease-in-out transform hover:-translate-y-1 hover:scale-105"
          >
            View Project
          </a>
        </div>
      </div>
      <div class="flex">
        <div
          class="bg-gray-200 rounded-lg shadow-md p-4 flex flex-col justify-between transition duration-300 ease-in-out transform hover:scale-105"
        >
          <div>
            <img
              src="/src/assets/pers.png"
              alt="PERS"
              class="w-full mb-4 rounded-lg"
            />
            <h2 class="text-gray-800 text-xl font-bold mb-2">
              Public Emergency Reporting System (Grad. Project)
            </h2>
            <p class="text-gray-800 text-sm mb-4">A web application and responsive mobile web that allows people report the emergencies with the related evidence(s). This project includes only the Mobile Web part.</p>
            <div class="mb-4">
              <span class="text-gray-800 text-sm font-semibold"
                >Used Tools:</span
              >
              <span class="text-gray-800 text-sm"> HTML, CSS, JavaScript, jQuery, Laravel, MySQL</span>
            </div>
          </div>
          <a
            href="https://github.com/huseyincanbay/pers_client_side_gradproject"
            target="_blank"
            rel="noopener noreferrer"
            class="bg-gradient-to-r from-purple-500 via-indigo-500 to-purple-600 hover:from-purple-600 hover:to-blue-500 text-white py-2 px-4 mt-3 rounded-lg block text-center transition duration-300 ease-in-out transform hover:-translate-y-1 hover:scale-105"
          >
            View Project
          </a>
        </div>
      </div>
    </div>
    <div class="text-center mt-14">
      <a
        href="https://github.com/huseyincanbay"
        target="_blank"
        rel="noopener noreferrer"
        class="bg-gray-300 text-gray-900 py-2 px-4 rounded-lg transition duration-300 ease-in-out transform hover:-translate-y-1 hover:scale-105 hover:bg-gray-900 hover:text-white hover:shadow-md"
      >
        See More Projects
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Projects",
};
</script>

<style scoped>
.container {
  max-width: 1200px;
}

.flex {
  flex: 1 1 0;
}

.transition {
  transition-property: all;
}

.ease-in-out {
  transition-timing-function: ease-in-out;
}

.transform {
  transform-origin: center;
}

.hover\:scale-105:hover {
  transform: scale(1.05);
}

.hover\:-translate-y-1:hover {
  transform: translateY(-1rem);
}
</style>
