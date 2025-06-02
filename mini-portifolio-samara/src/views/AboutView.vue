<template>
    <div>
        <h1 className="text-4xl md:text-5xl font-bold text-pink-700 text-center mt-20">Sobre Mim</h1>

        <div class="flex items-center justify-center min-h-screen mt-20">
            <div class="w-300  text-center p-6">
                <!-- Imagem -->
                <div
                    class="w-40 h-40 mb-5 mx-auto rounded-full bg-gradient-to-r from-blue-400 via-purple-500 to-pink-500 p-1 shadow-lg">
                    <img class="w-full h-full rounded-full object-cover" src="../assets/images/perfil.png"
                        alt="Samara image" />
                </div>

                <h2>
                    <stronger class="text-[30px] font-bold text-purple-900">Olá! Sou a Samara Adorno</stronger>
                </h2>
                <br>
                <p class="display-4 text-justify font-medium text-[20px] mt-5 mb-5 text-gray-900 mb-10">Estudante do
                    Curso Superior de Tecnologia em Análise e Desenvolvimento de Sistemas pela Universidade de Marília e
                    concluinte de um curso técnico integrado ao ensino médio pela Etec Antonio Devisate, atualmente
                    trabalho como operadora de telesserviços na Pascholoto Serviços Financeiros, estou em busca de uma
                    migração de carreira para a área de Tecnologia da Informação, pela qual estou estudando e buscando
                    conhecimento que me possibilitam realizar essa migração, através da minha graduação, eventos,
                    palestras, workshops, imersões, etc. Com isso, sou capaz de oferecer um serviço de qualidade através
                    de meus conhecimentos práticos da área de Tecnologia da Informação e boas habilidades interpessoais,
                    visando o meu desenvolvimento e aprimoramento profissional.</p>
                <p class="display-4 text-justify font-medium text-[20px] mt-5 mb-5 text-gray-900 mb-10">Sou uma pessoa
                    criativa, proativa, consigo trabalhar bem em equipe, além de ser uma pessoa bastante esforçada,
                    sempre procurando novas experiências para ampliar ainda mais meu conhecimento.</p>
            </div>
        </div>

        <!-- Formação -->
        <div class="flex items-center justify-center min-h-screen">
            <div class="w-200  text-center p-6">

                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <h2 class="text-center font-bold text-[30px] mt-5 mb-5 text-[#312d50]">
                        <span class="flex items-center gap-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor"
                                class="bi bi-mortarboard-fill text-blue-500" viewBox="0 0 16 16">
                                <path
                                    d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917z" />
                                <path
                                    d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466z" />
                            </svg>
                            <span>Formação Acadêmica</span>
                        </span>
                    </h2>
                </div>

                <ol class="relative border-s border-gray-200 dark:border-gray-700">
                    <li class="mb-10 ms-6">
                        <span
                            class="absolute flex items-center justify-center w-8 h-8 bg-purple-300 rounded-full -start-3 ring-8 ring-purple-300 dark:bg-blue-900">
                            <svg class="w-6 h-6 text-violet-800" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                                width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                                <path
                                    d="M12.4472 4.10557c-.2815-.14076-.6129-.14076-.8944 0L2.76981 8.49706l9.21949 4.39024L21 8.38195l-8.5528-4.27638Z" />
                                <path
                                    d="M5 17.2222v-5.448l6.5701 3.1286c.278.1325.6016.1293.8771-.0084L19 11.618v5.6042c0 .2857-.1229.5583-.3364.7481l-.0025.0022-.0041.0036-.0103.009-.0119.0101-.0181.0152c-.024.02-.0562.0462-.0965.0776-.0807.0627-.1942.1465-.3405.2441-.2926.195-.7171.4455-1.2736.6928C15.7905 19.5208 14.1527 20 12 20c-2.15265 0-3.79045-.4792-4.90614-.9751-.5565-.2473-.98098-.4978-1.27356-.6928-.14631-.0976-.2598-.1814-.34049-.2441-.04036-.0314-.07254-.0576-.09656-.0776-.01201-.01-.02198-.0185-.02991-.0253l-.01038-.009-.00404-.0036-.00174-.0015-.0008-.0007s-.00004 0 .00978-.0112l-.00009-.0012-.01043.0117C5.12215 17.7799 5 17.5079 5 17.2222Zm-3-6.8765 2 .9523V17c0 .5523-.44772 1-1 1s-1-.4477-1-1v-6.6543Z" />
                            </svg>

                        </span>
                        <h3 class="flex items-center mb-1 text-lg font-bold text-[24px] mt-5 mb-4 text-blue-900 ml-5">
                            Unimar Universidade de Marília, Marília
                        </h3>
                        <h4 class="font-bold text-[20px] mt-2 mb-3 text-gray-700">Curso Superior de Tecnologia (CST) em
                            Análise e Desenvolvimento de Sistemas
                        </h4>
                        <span class="display-4 text-center font-bold text-[16px] mt-4 text-gray-500">Janeiro 2024 -
                            Atual</span>
                    </li>
                    <li class="mb-10 ms-6">
                        <span
                            class="absolute flex items-center justify-center w-8 h-8 bg-purple-300 rounded-full -start-3 ring-8 ring-purple-300 dark:bg-blue-900">
                            <svg class="w-6 h-6 text-violet-800" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                                width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                                <path
                                    d="M9 6c0-1.65685 1.3431-3 3-3s3 1.34315 3 3-1.3431 3-3 3-3-1.34315-3-3Zm2 3.62992c-.1263-.04413-.25-.08799-.3721-.13131-1.33928-.47482-2.49256-.88372-4.77995-.8482C4.84875 8.66593 4 9.46413 4 10.5v7.2884c0 1.0878.91948 1.8747 1.92888 1.8616 1.283-.0168 2.04625.1322 2.79671.3587.29285.0883.57733.1863.90372.2987l.00249.0008c.11983.0413.24534.0845.379.1299.2989.1015.6242.2088.9892.3185V9.62992Zm2-.00374V20.7551c.5531-.1678 1.0379-.3374 1.4545-.4832.2956-.1034.5575-.1951.7846-.2653.7257-.2245 1.4655-.3734 2.7479-.3566.5019.0065.9806-.1791 1.3407-.4788.3618-.3011.6723-.781.6723-1.3828V10.5c0-.58114-.2923-1.05022-.6377-1.3503-.3441-.29904-.8047-.49168-1.2944-.49929-2.2667-.0352-3.386.36906-4.6847.83812-.1256.04539-.253.09138-.3832.13765Z" />
                            </svg>

                        </span>
                        <h3 class="flex items-center mb-1 text-lg font-bold text-[24px] mt-5 mb-4 text-blue-900 ml-5">
                            Etec Antônio Devisate, Marília
                        </h3>
                        <h4 class="font-bold text-[20px] mt-2 mb-3 text-gray-700">Curso Técnico Integrado ao Ensino
                            Médio em Desenvolvimento de Sistemas
                        </h4>
                        <span class="display-4 text-center font-bold text-[16px] mt-4 text-gray-500">Fevereiro 2021 –
                            Dezembro 2023</span>
                    </li>
                </ol>
            </div>
        </div>

        <!-- Trajetória Profissional -->
        <div class="flex items-center justify-center">
            <div class="w-full w-lg mx-w-600 px-6">
                <div class="flex flex-col items-center">
                    <h2 class="text-center font-bold text-[30px] mt-5 mb-5 text-[#312d50]">
                        <span class="flex items-center gap-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor"
                                class="bi bi-person-workspace text-green-500" viewBox="0 0 16 16">
                                <path
                                    d="M4 16s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1zm4-5.95a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5" />
                                <path
                                    d="M2 1a2 2 0 0 0-2 2v9.5A1.5 1.5 0 0 0 1.5 14h.653a5.4 5.4 0 0 1 1.066-2H1V3a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v9h-2.219c.554.654.89 1.373 1.066 2h.653a1.5 1.5 0 0 0 1.5-1.5V3a2 2 0 0 0-2-2z" />
                            </svg>
                            <span>Trajetória Profissional</span>
                        </span>
                    </h2>
                    <h3 class="text-center font-bold text-[24px] mt-5 mb-4 text-blue-900">Pascholoto Serviços
                        Financeiros</h3>
                    <h4 class="text-center font-bold text-[20px] mt-2 mb-7 text-gray-700">Operador de
                        Telemarketing Ativo e Receptivo</h4>
                    <span class="text-center font-bold text-[16px] mt-4 text-gray-500">Outubro 2024 - Atual</span>
                    <p class="text-justify font-medium text-[20px] mt-5 mb-5 text-gray-900">Operadora de
                        Telemarketing Ativa e Receptiva, representando o banco do Bradesco, atuando na parte de cobrança
                        referente a fatura de cartão de crédito.</p>
                    <p class="text-justify font-medium text-[20px] mt-5 mb-5 text-gray-900">
                        <stronger class="text-blue-900 font-bold">Competências:</stronger> Atendimento ao cliente ·
                        Habilidades analíticas · Suporte ao cliente · Negociação
                    </p>
                </div>
            </div>
        </div>

        <!-- Habilidades -->
        <div class="flex items-center justify-center min-h-screen mt-20">
            <div class="w-300  text-center">
                <div class="flex flex-col items-center">
                    <h2 class="text-center font-bold text-[30px] mt-5 mb-5 text-[#312d50]">
                        <span class="flex items-center gap-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor"
                                class="bi bi-star-fill text-yellow-500" viewBox="0 0 16 16">
                                <path
                                    d="M3.612 15.443c-.386.198-.824-.149-.746-.592l.83-4.73L.173 6.765c-.329-.314-.158-.888.283-.95l4.898-.696L7.538.792c.197-.39.73-.39.927 0l2.184 4.327 4.898.696c.441.062.612.636.282.95l-3.522 3.356.83 4.73c.078.443-.36.79-.746.592L8 13.187l-4.389 2.256z" />
                            </svg>
                            <span>Habilidades</span>
                        </span>
                    </h2>

                    <!-- Hard Skills -->
                    <h3 class="display-4 text-center font-bold text-[30px] mt-5 mb-4 text-blue-900">Hard skills</h3>

                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5 gap-4">
                        <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/skills/office.png"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Microsoft Office</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Conhecimento intermediário em ferramentas como Word, Excel, PowerPoint, Outlook, OneNote, Forms, Visio, etc.</p>
                        </div>

                        <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/skills/ui.png"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Conceitos de UX | UI</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Wireframe, Persona, Mapa de Empatia, Hierarquia, Prototipagem, Criação de slides, Criação de Logomarcas, etc.</p>
                        </div>

                       <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/skills/front.png"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Desenvolvimento Front-end</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Conhecimento em linguagens e ferramentas como HTML, CSS, JavaScript, Vue, Bootstrap, Tailwind CSS, etc.</p>
                        </div>

                       <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/skills/back.png"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Desenvolvimento Back-end</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Conhecimento em linguagens como C#, Python, PHP, etc.</p>
                        </div>

                        <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/skills/sofware.png"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Familiaridade com diversos softwares</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Figma, Canva, Git Hub, Thello, Pacote Adobe, Colors.io, Visiual Studio, Visual Studio Code, etc.</p>
                        </div>
                    </div>

                    <!-- Soft Skills -->
                    <h3 class="display-4 text-center font-bold text-[30px] mt-5 mb-4 text-blue-900">Soft skills</h3>

                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-5 gap-4">
                        <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Proatividade</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Solução de problemas, Iniciativa, Visão de futuro, Boa adaptação, Criatividade, etc</p>
                        </div>

                        <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/skills/office.png"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Microsoft Office</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Conhecimento intermediário em ferramentas como Word, Excel, PowerPoint, Outlook, OneNote, Forms, Visio, entre outras.</p>
                        </div>

                       <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/skills/office.png"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Microsoft Office</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Conhecimento intermediário em ferramentas como Word, Excel, PowerPoint, Outlook, OneNote, Forms, Visio, entre outras.</p>
                        </div>

                       <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Proatividade</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Solução de problemas, Iniciativa, Visão de futuro, Boa adaptação, Criatividade, etc</p>
                        </div>

                        <div
                            class="max-w-md h-100 p-6 bg-gradient-to-r from-blue-300 to-purple-400 border-3 border-violet-800 rounded-lg shadow-sm">
                            <div class="flex justify-center items-center">
                                <div
                                    class="w-20 h-20 lg:w-24 lg:h-24 rounded-full p-1">
                                    <img src="../assets/images/skills/office.png"
                                        class="w-full h-full object-cover">
                                </div>
                            </div>
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-pink-900">
                                    Microsoft Office</h5>
                            </a>
                            <p class="mb-3 font-semibold text-gray-900">Conhecimento intermediário em ferramentas como Word, Excel, PowerPoint, Outlook, OneNote, Forms, Visio, entre outras.</p>
                        </div>
                    </div>

                </div>
            </div>
        </div>

        <!-- Botão para a tela de projetos -->
        <div class="flex flex-col sm:flex-row gap-4 justify-center mt-20 mb-20">
            <button type="button"
                class="bg-gradient-to-r from-blue-600 to-purple-600 hover:from-blue-700 hover:to-purple-700 text-white px-3 py-3 transition-transform duration-300 transform hover:scale-105 font-semibold rounded-full text-[18px]">
                <router-link to="/contact" class="flex items-center gap-2">
                    <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="currentColor"
                        class="bi bi-headset" viewBox="0 0 16 16">
                        <path
                            d="M8 1a5 5 0 0 0-5 5v1h1a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V6a6 6 0 1 1 12 0v6a2.5 2.5 0 0 1-2.5 2.5H9.366a1 1 0 0 1-.866.5h-1a1 1 0 1 1 0-2h1a1 1 0 0 1 .866.5H11.5A1.5 1.5 0 0 0 13 12h-1a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h1V6a5 5 0 0 0-5-5" />
                    </svg>
                    <span>Entre em contato comigo</span>
                </router-link>
            </button>
        </div>

    </div>
</template>