<template>
    <div class="relative z-10 container mx-auto px-4 py-12">
        <div class="text-center mb-12">
            <h1 class="text-4xl md:text-5xl font-bold text-pink-700 text-center mt-20">Entre em Contato</h1>
            <p class="text-[20px] mt-5 text-gray-900 font-semibold max-w-3xl mx-auto">
            Tem alguma pergunta ou proposta? Estou à disposição para conversar! Preencha o formulário abaixo ou entre em
            contato através das minhas redes sociais.
          </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 max-w-6xl mx-auto">
            <!-- Formulário de contato -->
             <div class="bg-white-100 border border-white/20 rounded-lg p-8 shadow-lg">
            <h2 class="text-2xl font-bold text-pink-800  mb-6 flex items-center gap-2">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="30"
                height="30"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                strokeWidth="2"
                strokeLinecap="round"
                strokeLinejoin="round"
                class="text-pink-300"
              >
                <rect width="20" height="16" x="2" y="4" rx="2" />
                <path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7" />
              </svg>
              <span>Formulário de Contato</span> 
            </h2>

            <form class="space-y-6">
              <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="space-y-2">
                  <label htmlFor="name" class="block text-gray-900 text-[18px] font-semibold">
                    Nome
                  </label>
                  <input
                    type="text"
                    id="name"
                    class="w-full px-4 py-3 border border-gray-600 rounded-md text-black placeholder-gray-700 focus:outline-none focus:ring-2 focus:ring-pink-400"
                    placeholder="Seu nome"
                  />
                </div>
                <div class="space-y-2">
                  <label htmlFor="email" class="block text-gray-900 text-[18px] font-semibold">
                    Email
                  </label>
                  <input
                    type="email"
                    id="email"
                    class="w-full px-4 py-3 border border-gray-600 rounded-md text-black placeholder-gray-700 focus:outline-none focus:ring-2 focus:ring-pink-400"
                    placeholder="seu.email@exemplo.com"
                  />
                </div>
              </div>

              <div className="space-y-2">
                <label htmlFor="subject" class="block text-gray-900 text-[18px] font-semibold">
                  Assunto
                </label>
                <input
                  type="text"
                  id="subject"
                  className="w-full px-4 py-3 bg-white/20 border border-gray-600 rounded-md text-black placeholder-gray-700 focus:outline-none focus:ring-2 focus:ring-pink-400"
                  placeholder="Assunto da mensagem"
                />
              </div>

              <div className="space-y-2">
                <label htmlFor="message" class="block text-gray-900 text-[18px] font-semibold">
                  Mensagem
                </label>
                <textarea
                  id="message"
                  rows={5}
                  className="w-full px-4 py-3 bg-white/20 border border-gray-600 rounded-md text-black placeholder-gray-700 focus:outline-none focus:ring-2 focus:ring-pink-400 resize-none"
                  placeholder="Escreva sua mensagem aqui..."
                ></textarea>
              </div>

              <button
                type="submit"
                className="w-full py-3 px-6 bg-gradient-to-r from-pink-500 to-purple-600 text-white font-medium rounded-md hover:from-pink-600 hover:to-purple-700 transition-colors shadow-lg flex items-center justify-center gap-2"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="20"
                  height="20"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="currentColor"
                  strokeWidth="2"
                  strokeLinecap="round"
                  strokeLinejoin="round"
                >
                  <path d="m22 2-7 20-4-9-9-4Z" />
                  <path d="M22 2 11 13" />
                </svg>
                Enviar Mensagem
              </button>
            </form>
          </div>
          
          <div class="space-y-8">
            <!-- Informações de Contato -->
            <div class="bg-white-100 border border-white/20 rounded-lg p-8 shadow-lg">
              <h2 class="text-2xl font-bold text-pink-800  mb-6 flex items-center gap-2">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="currentColor"
                  strokeWidth="2"
                  strokeLinecap="round"
                  strokeLinejoin="round"
                  class="text-pink-300"
                >
                  <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z" />
                </svg>
                <span> Informações de Contato</span> 
              </h2>

              <div class="space-y-4">
                <div class="flex items-start gap-4">
                  <div class="w-10 h-10 rounded-full flex items-center justify-center flex-shrink-0">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="purple"
                      strokeWidth="2"
                      strokeLinecap="round"
                      strokeLinejoin="round"
                      class="text-white"
                    >
                      <path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z" />
                      <circle cx="12" cy="10" r="3" />
                    </svg>
                  </div>
                  <div>
                    <h3 class="text-gray-900 text-[18px] font-semibold">Localização</h3>
                    <p class="text-gray-700">
                      R. Luísa Rossi Oioli, 24 - Jardim Flora Rica, Marília - SP, 17513-440
                    </p>
                  </div>
                </div>

                <div class="flex items-start gap-4">
                  <div class="w-10 h-10 rounded-full flex items-center justify-center flex-shrink-0">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="purple"
                      strokeWidth="2"
                      strokeLinecap="round"
                      strokeLinejoin="round"
                      class="text-white"
                    >
                      <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z" />
                    </svg>
                  </div>
                  <div>
                    <h3 class="text-gray-900 text-[18px] font-semibold">Telefone</h3>
                    <p class="text-gray-700">+55 (14) 99689-7137</p>
                  </div>
                </div>

                <div class="flex items-start gap-4">
                  <div class="w-10 h-10 rounded-full flex items-center justify-center flex-shrink-0">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="purple"
                      strokeWidth="2"
                      strokeLinecap="round"
                      strokeLinejoin="round"
                      class="text-white"
                    >
                      <rect width="20" height="16" x="2" y="4" rx="2" />
                      <path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7" />
                    </svg>
                  </div>
                  <div>
                    <h3 class="text-gray-900 text-[18px] font-semibold">Email</h3>
                    <p class="text-gray-700">adornosamara165@gmail.com</p>
                  </div>
                </div>
              </div>
            </div>

            <!--  Redes Sociais  -->
            <div class="bg-white-100 border border-white/20 rounded-lg p-8 shadow-lg">
              <h2 class="text-2xl font-bold text-pink-800  mb-6 flex items-center gap-2">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="24"
                  height="24"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="purple"
                  strokeWidth="2"
                  strokeLinecap="round"
                  strokeLinejoin="round"
                  class="text-pink-300"
                >
                  <path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9" />
                  <path d="M13.73 21a2 2 0 0 1-3.46 0" />
                </svg>
                Redes Sociais
              </h2>

              <div class="grid grid-cols-2 gap-4">
                <a
                  href="https://www.linkedin.com/in/samara-adorno-91bb572a8"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="flex items-center gap-3 p-4 rounded-lg hover:bg-blue-300 transition-colors"
                >
                  <div class="w-10 h-10 rounded-full bg-blue-700 flex items-center justify-center">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      strokeWidth="2"
                      strokeLinecap="round"
                      strokeLinejoin="round"
                      class="text-white font-bold"
                    >
                      <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z" />
                      <rect width="4" height="12" x="2" y="9" />
                      <circle cx="4" cy="4" r="2" />
                    </svg>
                  </div>
                  <span class="text-gray-600 font-medium">LinkedIn</span>
                </a>

                <a
                  href="https://github.com/Samara-Adorno"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="flex items-center gap-3 p-4 rounded-lg hover:bg-gray-300 transition-colors"
                >
                  <div class="w-10 h-10 rounded-full bg-gray-700 flex items-center justify-center">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      strokeWidth="2"
                      strokeLinecap="round"
                      strokeLinejoin="round"
                      class="text-white font-bold"
                    >
                      <path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4" />
                      <path d="M9 18c-4.51 2-5-2-7-2" />
                    </svg>
                  </div>
                  <span class="text-gray-600 font-medium">GitHub</span>
                </a>

                <a
                  href="https://www.instagram.com/sa_adorno/"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="flex items-center gap-3 p-4 rounded-lg hover:bg-red-300 transition-colors"
                >
                  <div class="w-10 h-10 rounded-full bg-red-700 flex items-center justify-center">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      strokeWidth="2"
                      strokeLinecap="round"
                      strokeLinejoin="round"
                      class="text-white font-bold"
                    >
                      <rect width="20" height="20" x="2" y="2" rx="5" ry="5" />
                      <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z" />
                      <line x1="17.5" x2="17.51" y1="6.5" y2="6.5" />
                    </svg>
                  </div>
                  <span class="text-gray-600 font-medium">Instagram</span>
                </a>

                <a
                  href="https://www.facebook.com/samara.adorno.3"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="flex items-center gap-3 p-4 rounded-lg hover:bg-blue-300 transition-colors"
                >
                  <div class="w-10 h-10 rounded-full bg-blue-700 flex items-center justify-center">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="20"
                      height="20"
                      viewBox="0 0 24 24"
                      fill="none"
                      stroke="currentColor"
                      strokeWidth="2"
                      strokeLinecap="round"
                      strokeLinejoin="round"
                      class="text-white font-bold"
                    >
                      <path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z" />
                    </svg>
                  </div>
                  <span class="text-gray-600 font-medium">Facebook</span>
                </a>
              </div>
            </div>
        
        </div>
    </div>
</div>
</template>