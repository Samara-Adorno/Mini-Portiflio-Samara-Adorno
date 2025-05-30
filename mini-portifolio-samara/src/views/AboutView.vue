<template>
  <div>
  <h1 className="text-4xl md:text-5xl font-bold text-pink-700 text-center mt-20">Sobre Mim</h1>

  <div class="flex items-center justify-center min-h-screen bg-gray-100">
  <div class="w-500 bg-white border border-gray-200 rounded-lg shadow-sm  text-center p-6">
    <!-- Imagem -->
    <div class="w-40 h-40 mb-5 mx-auto rounded-full bg-gradient-to-r from-blue-400 via-purple-500 to-pink-500 p-1 shadow-lg">
    <img class="w-full h-full rounded-full object-cover" src="../assets/images/perfil.png" alt="Samara image" />
    </div>

    <h2><stronger class="text-[30px] font-bold text-purple-900">Olá! Sou a Samara Adorno</stronger></h2>
    <br>
    <p class="display-4 text-justify font-medium text-[20px] mt-5 mb-5 text-gray-900 mb-10">Estudante do Curso Superior de Tecnologia em Análise e Desenvolvimento de Sistemas pela Universidade de Marília e concluinte de um curso técnico integrado ao ensino médio pela Etec Antonio Devisate, atualmente trabalho como operadora de telesserviços na Pascholoto Serviços Financeiros, estou em busca de uma migração de carreira para a área de Tecnologia da Informação, pela qual estou estudando e buscando conhecimento que me possibilitam realizar essa migração, através da minha graduação, eventos, palestras, workshops, imersões, etc. Com isso, sou capaz de oferecer um serviço de qualidade através de meus conhecimentos práticos da área de Tecnologia da Informação e boas habilidades interpessoais, visando o meu desenvolvimento e aprimoramento profissional.</p>
    <p class="display-4 text-justify font-medium text-[20px] mt-5 mb-5 text-gray-900 mb-10">Sou uma pessoa criativa, proativa, consigo trabalhar bem em equipe, além de ser uma pessoa bastante esforçada, sempre procurando novas experiências para ampliar ainda mais meu conhecimento.</p>
  </div>
</div>

<div class="grid mt-10 mb-10 border border-gray-200 rounded-lg shadow-xs md:mb-12 md:grid-cols-2 bg-white">
    <!-- Formação -->
    <figure class="flex flex-col items-center justify-center p-8 text-center bg-white border-b border-gray-200 rounded-t-lg md:rounded-t-none md:rounded-ss-lg md:border-e">
        <blockquote class="max-w-2xl mx-auto mb-4 text-gray-500 lg:mb-8">
            <h2 class="display-4 text-center font-bold text-[30px] mt-5 mb-5 text-[#312d50]">Formação Acadêmica</h2>

            <h3 class="display-4 text-center font-bold text-[24px] mt-5 mb-4 text-blue-900">Unimar Universidade de Marília, Marília</h3>
            <h4 class="display-4 text-center font-bold text-[20px] mt-2 mb-3 text-gray-700">Curso Superior de Tecnologia (CST) em Análise e Desenvolvimento de Sistemas</h4>
            <span class="display-4 text-center font-bold text-[16px] mt-4 text-gray-500">Janeiro 2024 - Atual</span>

            <h3 class="display-4 text-center font-bold text-[24px] mt-10 mb-4 text-blue-900">Etec Antônio Devisate, Marília</h3>
            <h4 class="display-4 text-center font-bold text-[20px] mt-2 mb-3 text-gray-700">Curso Técnico Integrado ao Ensino Médio em Desenvolvimento de Sistemas</h4>
            <span class="display-4 text-center font-bold text-[16px] mt-4 text-gray-500">Fevereiro 2021 – Dezembro 2023</span>
        </blockquote>
    </figure>

    <!-- Experiência -->
    <figure class="flex flex-col items-center justify-center p-8 text-center bg-white border-b border-gray-200 md:rounded-se-lg">
        <blockquote class="max-w-2xl mx-auto mb-4 text-gray-500 lg:mb-8">
            <h2 class="display-4 text-center font-bold text-[30px] mt-5 mb-5 text-[#312d50]">Experiência</h2>
            
            <h3 class="display-4 text-center font-bold text-[24px] mt-5 mb-4 text-blue-900">Pascholoto Serviços Financeiros</h3>
            <h4 class="display-4 text-center font-bold text-[20px] mt-2 mb-7 text-gray-700">Operador de Telemarketing Ativo e Receptivo</h4>
            <p class="display-4 text-justify font-medium text-[20px] mt-5 mb-5 text-gray-900">Operadora de Telemarketing Ativa e Receptiva, representando o banco do Bradesco, atuando na parte de cobrança referente a fatura de cartão de crédito.</p>
            <p class="display-4 text-justify font-medium text-[20px] mt-5 mb-5 text-gray-900"><stronger class="text-blue-900 font-bold">Competências:</stronger> Atendimento ao cliente · Habilidades analíticas · Suporte ao cliente · Negociação</p>
        </blockquote>
    </figure>

    <!-- Habilidades -->
    <figure class="flex flex-col items-center justify-center p-8 text-center bg-white border-b border-gray-200 md:rounded-es-lg md:border-b-0 md:border-e">
        <blockquote class="max-w-2xl mx-auto mb-4 text-gray-500 lg:mb-8">
            <h2 class="display-4 text-center font-bold text-[30px] mt-5 mb-5 text-[#312d50]">Habilidades</h2>
            <ul class="text-gray-900 font-semibold text-[20px] p-4">
            <li>Microsoft Office</li>
            <li>Proatividade</li>
            <li>Conhecimento em conceitos de design</li>
            <li>Trabalho em equipe</li>
            <li>Conhecimento em conceitos de programação front-end Web</li>
            <li>Empatia</li>
            <li>Conhecimento em prototipagem</li>
            <li>Criatividade</li>
            <li>Criação de Logomarca</li>
            <li>Familiaridade com ferramentas e softwares da áreade TI</li>
            <li>Otimismo</li>
            <li>Conhecimento em linguagens da área de desenvolvimento</li>
            <li>Facilidade em aprendizado contínuo</li>
            </ul>
        </blockquote> 
    </figure>

    <!-- Objetivos -->
    <figure class="flex flex-col items-center justify-center p-8 text-center bg-white border-gray-200 rounded-b-lg md:rounded-se-lg">
        <blockquote class="max-w-2xl mx-auto mb-4 text-gray-500 lg:mb-8 dark:text-gray-400">
            <h2 class="display-4 text-center font-bold text-[30px] mt-5 mb-5 text-[#312d50]">Objetivos</h2>
            
          <ol class="text-gray-900 font-semibold text-[20px] p-4">
          <li>Estágio</li>
          <li>Web Designer</li>
          <li>UX / UI Design</li>
          <li>Marketing Digital</li>
          <li>Suporte Técnico</li>
          <li>Desenvolvedor Front - End</li>
          </ol>
        </blockquote>
    </figure>
</div>

     <!-- Botão para a tela de projetos -->
     <div class="flex flex-col sm:flex-row gap-4 justify-center mt-20 mb-20">
        <button type="button" class="bg-gradient-to-r from-blue-600 to-purple-600 hover:from-blue-700 hover:to-purple-700 text-white px-8 py-3 transition-transform duration-300 transform hover:scale-105 font-semibold rounded-full text-[18px]">
      <router-link to="/contact">
      <span>Entre em contato comigo</span>
      </router-link>
     </button>
     </div>
     </div>
</template>