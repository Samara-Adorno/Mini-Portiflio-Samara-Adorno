<template>
    <nav class="bg-linear-to-t from-[#a5a5ef] to-[#5c7ada] text-white py-4 px-8 flex justify-between items-center shadow-sm">
      <span class="self-center text-2xl font-semibold whitespace-nowrap text-white"><h1>Samara Adorno</h1></span>
      <div>
          <img src="../assets/images/logo.png" alt="Logo" class="rounded-full w-25 h-25 mx-auto md:mx-0 border-4 border-purple-300 shadow-lg object-cover">
        </div>
      <ul class="flex gap-6 mr-5 text-[20px]">
        <li><router-link to="/" class="block py-2 px-3 text-pink-900 font-bold  rounded-sm md:bg-transparent md:p-0" aria-current="page">Início</router-link></li>
        <li><router-link to="/about" class="block py-2 px-3 text-pink-700 font-semibold rounded-sm md:hover:bg-transparent md:hover:text-pink-800 md:p-0">Sobre</router-link></li>
        <li><router-link to="/project" class="block py-2 px-3 text-pink-700 font-semibold rounded-sm md:hover:bg-transparent md:hover:text-pink-800 md:p-0">Projetos</router-link></li>
        <li><router-link to="/contact" class="block py-2 px-3 text-pink-700 font-semibold rounded-sm md:hover:bg-transparent md:hover:text-pink-800 md:p-0">Contato</router-link></li>
      </ul>
    </nav>
</template>