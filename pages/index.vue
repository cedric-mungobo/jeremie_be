<template>
  <section
    class="ezy__header30 light relative overflow-hidden text-white bg-white z-10"
  >
    <div
      class="ezy__header30-topbar py-36 md:py-56 bg-center bg-no-repeat bg-cover relative flex items-center justify-center z-[1]"
      style="background-image: url(/assets/Couverture.jpg)"
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
    <div class="container px-4 mx-auto mb-2 -mt-36 md:-mt-48">
      <div class="z-10 relative mt-1">
        <section class="py-2 text-gray-100">
          <div class="container md:px-4 px-2 mx-auto">
            <div class="max-w-4xl mx-auto mb-6 text-center">
              <h2 class="text-2xl font-bold md:text-5xl">
                Choisissez le forfait de formation qui vous convient le mieux !
              </h2>
            </div>
            <div class="flex flex-wrap items-stretch -mx-4">
              <div class="flex w-full mb-8 sm:px-4 md:w-1/2 lg:w-1/2 lg:mb-0">
                <div
                  class="flex flex-grow flex-col p-6 space-y-6 rounded-xl shadow-md sm:p-8 bg-gray-400 text-black"
                >
                  <div class="space-y-1">
                    <h4 class="text-2xl font-bold">Forfait</h4>
                    <span class="text-4xl font-bold">Découverte</span>
                  </div>
                  <p class="mt-0 leading-relaxed text-gray-800">
                    {{ package1.time }}
                  </p>
                  <span class="p-0"
                    >Début de la séance : Ce 01 septembre 2024
                  </span>
                  <ul class="flex-1 mb-6 text-gray-800">
                    <li
                      class="flex mb-2 space-x-2"
                      v-for="(item, i) in package1.contenu"
                      :key="i"
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                        class="flex-shrink-0 w-6 h-6 text-gray-800"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                          clip-rule="evenodd"
                        ></path>
                      </svg>
                      <span>{{ item }}</span>
                    </li>
                    <span class="mb-2"> Inclus </span>

                    <li
                      class="flex mb-2 space-x-2"
                      v-for="(item, i) in package1.inclus"
                      :key="i"
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                        class="flex-shrink-0 w-6 h-6 text-gray-800"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                          clip-rule="evenodd"
                        ></path>
                      </svg>
                      <span>{{ item }}</span>
                    </li>
                  </ul>
                  <button
                    type="button"
                    class="inline-block px-5 py-3 font-semibold tracking-wider text-center rounded-lg bg-gradient-to-r from-black to-slate-800 text-gray-100"
                  >
                    Optez pour votre formation
                  </button>
                </div>
              </div>
              <div class="flex w-full mb-8 sm:px-4 md:w-1/2 lg:w-1/2 lg:mb-0">
                <div
                  class="flex flex-grow flex-col p-6 space-y-6 rounded-xl shadow sm:p-8 bg-gradient-to-r from-black to-slate-800 text-gray-100"
                >
                  <div class="space-y-2">
                    <h4 class="text-2xl font-bold">Forfait</h4>
                    <span class="text-4xl font-bold">Intermédiaire </span>
                  </div>
                  <p class="leading-relaxed">
                    {{ package2.time }}
                  </p>
                  <p class="p-0">Début de la séance : Ce 01 septembre 2024</p>
                  <ul class="flex-1 space-y-2">
                    <li
                      class="flex mb-2 space-x-2"
                      v-for="(item, i) in package2.contenu"
                      :key="i"
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                        class="flex-shrink-0 w-6 h-6 text-gray-100"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                          clip-rule="evenodd"
                        ></path>
                      </svg>
                      <span>{{ item }}</span>
                    </li>

                    <p>Inclus</p>

                    <li
                      class="flex mb-2 space-x-2"
                      v-for="(item, i) in package2.inclus"
                      :key="i"
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                        class="flex-shrink-0 w-6 h-6 text-gray-100"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                          clip-rule="evenodd"
                        ></path>
                      </svg>
                      <span>{{ item }}</span>
                    </li>
                  </ul>
                  <a
                    rel="noopener noreferrer"
                    href="#"
                    class="inline-block w-full px-5 py-3 font-bold tracking-wider text-center rounded-lg bg-gray-300 text-gray-900"
                    >Optez pour votre formation
                  </a>
                </div>
              </div>
            </div>
          </div>
        </section>
      </div>
    </div>

    <section class="md:py-10">
      <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div
          class="lg:py-14 lg:px-20 md:p-10 px-5 py-10 rounded-2xl bg-gradient-to-r from-indigo-600 to-violet-600 flex items-center justify-between flex-col lg:flex-row"
        >
          <div class="block text-center mb-5 lg:text-left lg:mb-0">
            <h2
              class="font-manrope text-4xl text-white font-semibold mb-5 lg:mb-2"
            >
              COACHING PERSONNALISÉ
            </h2>
            <p class="text-xl text-indigo-100">
              Ces deux forfaits sont conçus pour répondre aux besoins variés des
              créateurs de contenu, allant de ceux qui débutent dans le domaine
              à ceux qui souhaitent approfondir et monétiser leur présence en
              ligne. Chaque forfait est accompagné d’un soutien pratique et
              théorique, avec des avantages supplémentaires dans le Forfait
              Intermédiaire pour une formation plus complète.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section
      class="ezy__about12 light py-14 md:py-24 bg-white dark:bg-[#0b1727] text-zinc-900 dark:text-white"
    >
      <div class="container px-4">
        <div class="grid grid-cols-12 gap-5 justify-center items-center">
          <div class="col-span-12 lg:col-span-6">
            <div class="lg:px-7">
              <h1
                class="uppercase text-2xl md:text-4xl leading-tight font-medium mb-2"
              >
                JEREMIE B. ELONGA (Jeremie Be)
              </h1>
              <p class="text-lg leading-normal opacity-75 my-6">
                Jeremie Be est un passionné de l'image et du business en général
                depuis 2011, lorsqu'il s'est lancé dans la photographie et la
                vidéo. Aujourd'hui, il possède une société de production en RDC,
                Beprogroupe, qui lui a permis de travailler avec plusieurs
                entreprises nationales et multinationales.
              </p>
              <p class="text-lg leading-normal opacity-75 my-6">
                En plus de cela, Jeremie Be a créé BEART, une galerie d'art qui
                a généré un chiffre d'affaires de plus de 30 000 $ depuis 2022 .
                En 2020, il a décidé de faire découvrir son pays, la RDC, en
                voyageant à travers plus de 20 provinces pour y créer des
                documentaires.
              </p>
              <p class="text-lg leading-normal opacity-75 my-6">
                En plus de cela, Jeremie Be a créé BEART, une galerie d'art qui
                a généré un chiffre d'affaires de plus de 30 000 $ depuis 2022 .
                En 2020, il a décidé de faire découvrir son pays, la RDC, en
                voyageant à travers plus de 20 provinces pour y créer des
                documentaires.
              </p>
              <p class="text-lg leading-normal opacity-75 my-6">
                En 2023, il s'est lancé comme YouTubeur, et sa chaîne lui permet
                de gagner entre 800 $ et 1 000 $ par mois. Aujourd'hui, il
                continue de développer son projet "Made in Africa", qui valorise
                la culture africaine. Jeremie Be a déjà voyagé dans plusieurs
                pays africains tels que la Côte d'Ivoire, le Rwanda, la Zambie,
                le Congo-Brazzaville et le Gabon.
              </p>
            </div>
          </div>
          <div class="col-span-12 lg:col-span-6">
            <div class="flex justify-center lg:justify-start lg:ml-12">
              <img
                src="/assets/Jeremie.jpg"
                alt=""
                class="max-w-full h-auto rounded-xl"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
  </section>
</template>

<script lang="ts" setup>
const package1 = {
  time: " 4 séances (2 heures par séance) / 2 séances par semaine",
  contenu: [
    "Introduction à la Création de Contenu",
    "Stratégie de Contenu qui Marche sur les Réseaux Sociaux",
    "Personal Branding",
    "Parler Devant sa Caméra avec Confiance",
    "Création de Contenu sur YouTube",
    "Création de Contenu sur Instagram",
    "Création de Contenu sur Facebook",
    "Création de votre Kit Média",
  ],
  inclus: ["Accès aux supports PDF", "Session de Q&A de 30 minutes"],
};
const package2 = {
  time: " 8 séances (2 heures par séance) / 2 séances par semaine",
  contenu: [
    "Tous les modules du Forfait Découverte",
    "Monétiser son Instagram et Facebook",
    "Gestion et Planification de Contenu",
    "Analyse des Résultats et Optimisation",
    "Utilisation de Matériel (équipements & logiciels)",
    "Création de votre Kit Média (approfondi)",
  ],
  inclus: ["Accès aux supports PDF", "Session de Q & A de 1 heure"],
};
</script>

