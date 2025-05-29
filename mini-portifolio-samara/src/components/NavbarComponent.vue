<template>
    <nav class="bg-[#a5a5ef] shadow-sm text-white py-4 px-8 flex justify-between items-center">
      <a href="#" class="flex items-center space-x-3 rtl:space-x-reverse">
      <img src="https://flowbite.com/docs/images/logo.svg" class="h-8" alt="Logo">
      <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white"><h1>Samara Adorno</h1></span>
      </a>
      <ul class="flex gap-6">
        <li><router-link to="/" class="block py-2 px-3 text-white bg-blue-700 font-semibold rounded-sm md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-blue-500" aria-current="page">Início</router-link></li>
        <li><router-link to="/about" class="block py-2 px-3 text-gray-900 font-semibold rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Sobre</router-link></li>
        <li><router-link to="/project" class="block py-2 px-3 text-gray-900 font-semibold rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Projetos</router-link></li>
        <li><router-link to="/contact" class="block py-2 px-3 text-gray-900 font-semibold rounded-sm hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Contato</router-link></li>
      </ul>
    </nav>
</template>