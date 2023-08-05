<template>
  <div
    class="bg-gray-900 flex flex-col items-center justify-center"
    id="experiences"
  >
    <header class="bg-gray">
      <div class="max-w-7xl mx-auto py-4 px-4 sm:px-6 lg:px-8">
        <h1 class="text-3xl font-semibold text-white pt-8 pb-4 mt-4 mb-4">
          Work Experience
        </h1>
        <div class="border-t-2 border-gray"></div>
      </div>
    </header>

    <main class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
      <div class="flex flex-col md:flex-row">
        <div class="w-2 h-full bg-gray-300 md:w-px"></div>
        <div class="md:pl-8 mb-12">
          <div class="mb-12">
            <div class="bg-gray-800 p-6 rounded-lg">
              <h2 class="text-xl font-semibold text-white mb-2">KKTCELL</h2>
              <p class="text-gray-400">Nov 2021 - Apr 2022</p>
              <h3 class="text-lg font-medium mt-2 text-white">
                SQL Solution Consultant
              </h3>
              <ul class="text-gray-200 list-disc list-inside">
                <li class="text-white font-normal">
                  Detailed information requested by other departments was
                  accessed by writing SQL queries and turned into reports.
                </li>
                <li class="text-white font-normal">
                  Provided solutions to the data-derived problems experienced by
                  field teams in the quarantine initiation, retrieval and
                  termination processes of tracking devices.
                </li>
                <li class="text-white font-normal">
                  Assisted with the maintenance of the product and gave feedback
                  to technical team regarding the analyzes made.
                </li>
              </ul>
            </div>
          </div>
          <div class="mb-8">
            <div class="bg-gray-800 p-6 rounded-lg">
              <h2 class="text-xl font-semibold text-white mb-2">
                NANO YAZILIM VE TEKNOLOJİ HİZMETLERİ
              </h2>
              <p class="text-gray-400">Aug 2021 - Sep 2021</p>
              <h3 class="text-lg font-medium mt-2 text-white">
                Intern Software Engineer
              </h3>
              <ul class="text-gray-200 list-disc list-inside">
                <li class="text-white font-normal">
                  Completed the task of rebuilding the Front End parts of the
                  company's past project by using HTML, CSS, Bootstrap and
                  JavaScript.
                </li>
                <li class="text-white font-normal">
                  Implemented back-end functionality to support user
                  authentication and data storage in a project by using PHP and
                  MySQL.
                </li>
                <li class="text-white font-normal">
                  Designed and implemented relational databases to store and
                  manage structured data by using MySQL
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>


<script>
export default {
  name: "Experiences",
};
</script>

<style>
@media (max-width: 640px) {
  .md\:pl-8 {
    padding-left: 1rem !important;
    padding: 12px;
  }
}
</style>
