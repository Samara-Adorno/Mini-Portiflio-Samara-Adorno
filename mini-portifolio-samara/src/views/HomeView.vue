<template>
  <div class="flex-col items-center justify-center px-6 py-20 text-center">

    <!-- Imagem de perfil -->
    <div
      class="relative mx-auto border-gray-800 dark:border-gray-800 bg-gray-800 border-[8px] rounded-t-xl h-[172px] max-w-[301px] md:h-[294px] md:max-w-[512px] mt-30">
      <div class="rounded-lg overflow-hidden h-[156px] md:h-[278px] bg-white">
        <img src="../assets/images/Samara.png" class="h-[156px] md:h-[278px] w-full rounded-lg" alt="Samara Perfil">
      </div>
    </div>
    <div
      class="relative mx-auto bg-gray-900 rounded-b-xl rounded-t-sm h-[17px] max-w-[351px] md:h-[21px] md:max-w-[597px]">
      <div
        class="absolute left-1/2 top-0 -translate-x-1/2 rounded-b-xl w-[56px] h-[5px] md:w-[96px] md:h-[8px] bg-gray-800">
      </div>
    </div>
    <div class="flex justify-center">
    </div>

    <!-- Introdução -->
    <div class="max-w-4xl mx-auto space-y-6 m-10">
      <div class="space-y-2">
        <h3 class="text-slate-600 display-4 text-center font-bold text-[32px] mt-5 mb-5 text-[#312d50]">Olá, eu sou</h3>
        <h1
          class="text-4xl md:text-6xl font-bold text-slate-800 bg-gradient-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent text-center">
          Samara Adorno
        </h1>
        <h2 class="font-semibold display-4 text-center font-bold text-[35px] mt-5 mb-5 text-blue-500">Desenvolvedora
          Full Stack</h2>
      </div>

      <p class="display-4 text-center font-bold text-[20px] mt-5 mb-5 text-gray-900 mb-10">
        Técnica em Desenvolvimento de Sistemas e aluna de graduação em Análise e Desenvolvimento de Sistemas pela
        Universidade de Marília. Sou apaixonada por criar interfaces incríveis por meio do desenvolvimento web, possuo
        experiência em tecnologias modernas e sempre em busca de novos desafios, principalmente em relação a uma
        possível migração profissional para alguma carreira na área de Tecnologia da Informação.
      </p>
    </div>

    <!-- Botão para a tela de projetos -->
    <div class="flex flex-col sm:flex-row gap-4 justify-center mt-20 mb-20">
      <button type="button"
        class="bg-gradient-to-r from-blue-600 to-purple-600 hover:from-blue-700 hover:to-purple-700 text-white px-3 py-3 transition-transform duration-300 transform hover:scale-105 font-semibold rounded-full text-[18px]">
        <router-link to="/project" class="flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="currentColor" class="bi bi-eye-fill"
            viewBox="0 0 16 16">
            <path d="M10.5 8a2.5 2.5 0 1 1-5 0 2.5 2.5 0 0 1 5 0" />
            <path d="M0 8s3-5.5 8-5.5S16 8 16 8s-3 5.5-8 5.5S0 8 0 8m8 3.5a3.5 3.5 0 1 0 0-7 3.5 3.5 0 0 0 0 7" />
          </svg>
          <span>Veja meus Projetos</span>
        </router-link>
      </button>
    </div>

  </div>
</template>