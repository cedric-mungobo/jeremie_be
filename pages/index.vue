<template>
  <section
    class="ezy__header30 light relative overflow-hidden text-white bg-white dark:bg-[#0b1727] z-10"
  >
    <div
      class="ezy__header30-topbar py-36 md:py-56 bg-center bg-no-repeat bg-cover relative flex items-center justify-center z-[1]"
      style="
        background-image: url(https://cdn.easyfrontend.com/pictures/contents/contents-banner.jpg);
      "
    >
      <div
        class="absolute top-0 left-0 right-0 bottom-0 bg-black bg-opacity-60 -z-10"
      ></div>
      <div class="container px-4 mx-auto">
        <div class="max-w-5xl flex justify-center text-center mx-auto">
          <div>
            <h1 class="text-3xl font-bold leading-tight md:text-6xl mb-6">
              Lancez-vous sur Internet avec confiance, que vous soyez amateur ou
              professionnel !
            </h1>
            <div class="max-w-lg flex justify-center mx-auto">
              <div class="text-center">
                <p class="text-xl opacity-80 leading-snug">
                  COACHING PERSONNALISÉ est une formation d'accompagnement 100%
                  en ligne, créée par Jeremie B.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- courses carousel -->
    <div class="container px-4 mx-auto mb-2 -mt-28 md:-mt-48">
      <div class="z-10 relative mt-12">
        <div class="grid grid-cols-6 gap-x-6">
          <!-- card item -->
          <div class="col-span-6 md:col-span-2">
            <div class="rounded-lg overflow-hidden mt-6 lg:mt-0">
              <div class="relative">
                <img
                  src="https://cdn.easyfrontend.com/pictures/featured/featured_10_1.png"
                  alt=""
                  class="w-full rounded-b-xl"
                />
                <div
                  class="absolute bottom-0 flex flex-col justify-center items-center w-full text-white px-12 pb-6 text-center"
                >
                  <h4 class="text-[22px] leading-none font-medium mb-0">
                    Technology
                  </h4>
                  <p class="opacity-75 mb-4">17 courses</p>
                  <NuxtLink
                    to="/details"
                    class="bg-blue-600 hover:bg-opacity-90 text-white py-3 rounded duration-300 px-9 mb-3"
                    >View All</NuxtLink
                  >
                </div>
              </div>
            </div>
          </div>
          <!-- card item -->
          <div class="col-span-6 md:col-span-2">
            <div class="rounded-lg overflow-hidden mt-6 lg:mt-0">
              <div class="relative">
                <img
                  src="https://cdn.easyfrontend.com/pictures/featured/featured_10_2.png"
                  alt=""
                  class="w-full roulg"
                />
                <div
                  class="absolute bottom-0 flex flex-col justify-center items-center w-full text-white px-12 pb-6 text-center"
                >
                  <h4 class="text-[22px] leading-none font-medium mb-0">
                    Marketing
                  </h4>
                  <p class="opacity-75 mb-4">22 courses</p>
                  <NuxtLink
                    to="/details"
                    class="bg-blue-600 hover:bg-opacity-90 text-white py-3 rounded duration-300 px-9 mb-3"
                    >View All</NuxtLink
                  >
                </div>
              </div>
            </div>
          </div>
          <!-- card item -->
          <div class="col-span-6 md:col-span-2">
            <div class="rounded-lg overflow-hidden mt-6 lg:mt-0">
              <div class="relative">
                <img
                  src="https://cdn.easyfrontend.com/pictures/featured/featured_10_4.png"
                  alt=""
                  class="w-full"
                />
                <div
                  class="absolute bottom-0 flex flex-col justify-center items-center w-full text-white px-12 pb-6 text-center"
                >
                  <h4 class="text-[22px] leading-none font-medium mb-0">
                    Designing
                  </h4>
                  <p class="opacity-75 mb-4">09 courses</p>
                  <NuxtLink
                    to="/details"
                    class="bg-blue-600 hover:bg-opacity-90 text-white py-3 rounded duration-300 px-9 mb-3"
                    >View All</NuxtLink
                  >
                </div>
              </div>
            </div>
          </div>
        </div>

        <button
          class="w-12 h-12 text-[22px] bg-blue-600 bg-opacity-70 hover:bg-opacity-100 text-white rounded-full absolute top-2/4 -left-6 -translate-y-1/2 transition"
        >
          <i class="fas fa-angle-left"></i>
        </button>
        <button
          class="w-12 h-12 text-[22px] bg-blue-600 bg-opacity-70 hover:bg-opacity-100 text-white rounded-full absolute top-2/4 -right-6 -translate-y-1/2 transition"
        >
          <i class="fas fa-angle-right"></i>
        </button>
      </div>
    </div>

    <section
      class="ezy__team8 light bg-slate-100 text-zinc-900 overflow-hidden"
    >
      <div class="ezy__team8-list">
        <div class="container px-4 mx-auto">
          <div class="flex flex-col md:flex-row">
            <div class="w-full md:w-1/2 md:order-2">
              <div
                class="bg-center bg-no-repeat bg-cover min-h-[250px] w-full md:w-[50vw] h-full"
                style="
                  background-image: url(https://cdn.easyfrontend.com/pictures/team/team_8.png);
                "
              ></div>
            </div>
            <div class="w-full md:w-1/2 relative">
              <div class="pt-12 pb-28 md:py-24 lg:py-48 lg:pr-24">
                <h4 class="font-medium text-2xl mb-1">Raima Ray</h4>
                <p class="mb-6">Business Head</p>

                <p class="opacity-50 mb-0 leading-7">
                  It’s easier to reach your savings goals when you have the
                  right savings account. Take a look and find the right one for
                  you.It’s easier to reach your savings goals when you have the
                  right savings account. Take a look and find the right one for
                  youIt’s easier to reach your savings goals when you have the
                  right savings account. Take a look and find the right one for
                  you!
                </p>
                <div class="mt-6">
                  <NuxtLink
                    to="/details"
                    class="inline-block opacity-60 transition duration-300 hover:translate-y-1 hover:opacity-100 mr-4"
                    ><span class="fab fa-facebook-f"></span
                  ></NuxtLink>
                  <a
                    href="#"
                    class="inline-block opacity-60 transition duration-300 hover:translate-y-1 hover:opacity-100 mr-4"
                    ><span class="fab fa-linkedin-in"></span
                  ></a>
                  <a
                    href="#"
                    class="inline-block opacity-60 transition duration-300 hover:translate-y-1 hover:opacity-100 mr-4"
                    ><span class="fab fa-twitter"></span
                  ></a>
                  <a
                    href="#"
                    class="inline-block opacity-60 transition duration-300 hover:translate-y-1 hover:opacity-100"
                    ><span class="fab fa-behance"></span
                  ></a>
                </div>
              </div>

              <div
                class="absolute w-24 text-right right-[13%] bottom-0 text-[150px] text-blue-200 dark:text-slate-700 font-medium"
              >
                1
              </div>

              <div class="-mt-10 -translate-y-7">
                <button
                  class="w-10 h-10 text-[12px] bg-transparent rounded-full border border-slate-400 inline-flex justify-center items-center transition duration-300 hover:bg-slate-300 dark:hover:bg-slate-700 mr-3"
                >
                  <i class="fas fa-chevron-left"></i>
                </button>
                <button
                  class="w-10 h-10 text-[12px] bg-transparent rounded-full border border-slate-400 inline-flex justify-center items-center transition duration-300 hover:bg-slate-300 dark:hover:bg-slate-700"
                >
                  <i class="fas fa-chevron-right"></i>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </section>
</template>

<script lang="ts" setup>
</script>

