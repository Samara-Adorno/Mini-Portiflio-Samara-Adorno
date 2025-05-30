<template>
  <div>
    <h2 class="display-4 text-center font-bold text-[32px] mt-5 mb-5 text-[#312d50]">Seja bem-vindo(a)!</h2>
    <h3 class="display-4 text-center font-bold text-[24px] mt-5 mb-5 text-blue-900">Mini Portifólio</h3>

    <h1 class="display-4 text-center font-bold text-[50px] mt-5 mb-5 text-purple-900">SAMARA ADORNO</h1>
    <p class="display-4 text-center font-bold text-[20px] mt-5 mb-5 text-pink-900 mb-10"><i>Técnica em Desenvolvimento de Sistemas | Aluna do curso de Análise e Desenvolvimento de Sistemas na Universidade de Marília</i></p>
  </div>
  <div class="relative mx-auto border-gray-800 dark:border-gray-800 bg-gray-800 border-[8px] rounded-t-xl h-[172px] max-w-[301px] md:h-[294px] md:max-w-[512px]">
    <div class="rounded-lg overflow-hidden h-[156px] md:h-[278px] bg-white dark:bg-gray-800">
        <img src="../assets/images/Samara.png" class="dark:hidden h-[156px] md:h-[278px] w-full rounded-lg" alt="">
    </div>
    </div>
    <div class="relative mx-auto bg-gray-900 dark:bg-gray-700 rounded-b-xl rounded-t-sm h-[17px] max-w-[351px] md:h-[21px] md:max-w-[597px]">
    <div class="absolute left-1/2 top-0 -translate-x-1/2 rounded-b-xl w-[56px] h-[5px] md:w-[96px] md:h-[8px] bg-gray-800"></div>
  </div>
  <div class="flex justify-center">
  <button type="button" class="text-white bg-purple-700 hover:bg-violet-700 focus:outline-none focus:ring-4 focus:ring-purple-300 font-semibold rounded-full text-[16px] px-5 py-2.5 text-center mt-10 mb-10 dark:bg-purple-600 dark:hover:bg-purple-700 dark:focus:ring-purple-900 transition duration-300 transition-transform duration-300 transform hover:scale-105">
  <router-link to="/project">
  <span>Conheça meus projetos</span>
  </router-link>
  </button>
  </div>
</template>