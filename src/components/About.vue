<template>
  <div class="dark:bg-gray-900 min-h-screen" id="about">
    <div class="container mx-auto px-4 py-12 flex flex-wrap">
      <div class="img w-full md:w-1/2 flex justify-center items-center">
        <img src="/src/assets/undraw_stars_re_6je7.svg" alt="Image" class="w-2/3" />
      </div>
      <div class="w-full md:w-1/2">
        <h1
          class="text-4xl font-bold text-gray-800 dark:text-white mb-6 mt-12 text-center md:text-left"
        >
          About Me
        </h1>
        <p
          class="text-lg text-gray-700 dark:text-gray-300 leading-relaxed mb-6"
        >
          I am a Software Engineer with a strong passion for technology. I
          consider myself a quick learner, disciplined and dedicated person. I
          thoroughly enjoy working with different technologies and exploring new
          possibilities in the world of software development. My goal is to
          contribute to innovative projects and create solutions that make a
          positive impact.
        </p>
        <div>
          <h2
            class="text-4xl font-bold text-gray-800 dark:text-white mb-6 text-center md:text-left"
          >
            Education
          </h2>
          <div class="mb-6">
            <h3 class="text-1lg font-bold text-gray-700 dark:text-gray-300 mb-1">
              Eastern Mediterranean University | Bachelor's Degree in Software Engineering
            </h3>
            <p class="font-bold text-gray-600 dark:text-gray-400 text-sm mt-3">Sep 2017 - Feb 2023</p>
            <p
              class="text-lg text-gray-700 dark:text-gray-300 leading-relaxed mt-2"
            >
              I am graduated from Eastern Mediterranean University with a
              Bachelor's Degree in Software Engineering. I
              have had the opportunity to acquire valuable knowledge and skills
              during my studies at the University. Courses such
              as Algorithms, Data Structures, Operating Systems, and Computer
              Networks have played a crucial role in shaping my software
              engineering mindset and establishing a strong foundation.
              Additionally, I have gained practical experience by working on
              various software projects and writing comprehensive reports on
              Software Process and Management, Software Requirement Specification,
              Software Design, and Software Quality Assurance & Testing. These
              experiences have honed my ability to approach software development
              with precision and attention to detail, ensuring the delivery of
              high-quality solutions.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
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
