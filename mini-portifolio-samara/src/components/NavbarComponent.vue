<template>
  <nav class="bg-gradient-to-t from-[#a5a5ef] to-[#5c7ada] text-white py-4 px-4 md:px-8 shadow-sm">
    <!-- Desktop Layout -->
    <div class="hidden md:grid md:grid-cols-3 items-center">
      <!-- Nome -->
      <div class="justify-self-start">
        <span class="text-xl lg:text-2xl font-semibold whitespace-nowrap text-white">
          <h1>Samara Adorno</h1>
        </span>
      </div>
      
      <!-- Logo -->
      <div class="flex justify-center items-center">
        <div class="w-20 h-20 lg:w-24 lg:h-24 rounded-full bg-gradient-to-r from-blue-400 to-purple-500 p-1">
          <img src="../assets/images/logo.png" alt="Logo" class="w-full h-full rounded-full object-cover">
        </div>
      </div>
      
      <!-- Menu Desktop -->
      <div class="justify-self-end">
        <ul class="flex gap-4 lg:gap-6 text-lg lg:text-[20px]">
          <li><router-link to="/" class="block py-2 px-3 text-pink-900 font-bold rounded-sm hover:text-pink-800 transition-colors" aria-current="page">Início</router-link></li>
          <li><router-link to="/about" class="block py-2 px-3 text-pink-700 font-semibold rounded-sm hover:text-pink-800 transition-colors">Sobre</router-link></li>
          <li><router-link to="/project" class="block py-2 px-3 text-pink-700 font-semibold rounded-sm hover:text-pink-800 transition-colors">Projetos</router-link></li>
          <li><router-link to="/contact" class="block py-2 px-3 text-pink-700 font-semibold rounded-sm hover:text-pink-800 transition-colors">Contato</router-link></li>
        </ul>
      </div>
    </div>

    <!-- Mobile Layout -->
    <div class="md:hidden">
      <!-- Header Mobile -->
      <div class="flex justify-between items-center">
        <!-- Nome -->
        <span class="text-lg font-semibold text-white">
          <h1>Samara Adorno</h1>
        </span>

        <!-- Logo -->
        <div class="w-16 h-16 rounded-full bg-gradient-to-r from-blue-400 to-purple-500 p-1">
          <img src="../assets/images/logo.png" alt="Logo" class="w-full h-full rounded-full object-cover">
        </div>

        <!-- Botão Menu Hambúrguer -->
        <button 
          @click="toggleMobileMenu" 
          class="text-white focus:outline-none focus:ring-2 focus:ring-white/50 rounded-md p-2"
          :aria-expanded="isMobileMenuOpen"
          aria-label="Toggle navigation menu"
        >
          <!-- Ícone Hambúrguer -->
          <svg v-if="!isMobileMenuOpen" class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
          </svg>
          <!-- Ícone X -->
          <svg v-else class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
          </svg>
        </button>
      </div>

      <!-- Menu Mobile (Dropdown) -->
      <div 
        v-show="isMobileMenuOpen" 
        class="mt-4 pb-4 border-t border-white/20"
        :class="{ 'animate-fade-in': isMobileMenuOpen }"
      >
        <ul class="flex flex-col space-y-2 mt-4">
          <li>
            <router-link 
              to="/" 
              @click="closeMobileMenu"
              class="block py-3 px-4 text-pink-900 font-bold rounded-md hover:bg-white/10 transition-colors" 
              aria-current="page"
            >
              Início
            </router-link>
          </li>
          <li>
            <router-link 
              to="/about" 
              @click="closeMobileMenu"
              class="block py-3 px-4 text-pink-700 font-semibold rounded-md hover:bg-white/10 hover:text-pink-800 transition-colors"
            >
              Sobre
            </router-link>
          </li>
          <li>
            <router-link 
              to="/project" 
              @click="closeMobileMenu"
              class="block py-3 px-4 text-pink-700 font-semibold rounded-md hover:bg-white/10 hover:text-pink-800 transition-colors"
            >
              Projetos
            </router-link>
          </li>
          <li>
            <router-link 
              to="/contact" 
              @click="closeMobileMenu"
              class="block py-3 px-4 text-pink-700 font-semibold rounded-md hover:bg-white/10 hover:text-pink-800 transition-colors"
            >
              Contato
            </router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      isMobileMenuOpen: false
    }
  },
  methods: {
    toggleMobileMenu() {
      this.isMobileMenuOpen = !this.isMobileMenuOpen
    },
    closeMobileMenu() {
      this.isMobileMenuOpen = false
    }
  },
  mounted() {
    // Fechar menu ao redimensionar para desktop
    window.addEventListener('resize', () => {
      if (window.innerWidth >= 768) {
        this.isMobileMenuOpen = false
      }
    })
  }
}
</script>

<style scoped>
.animate-fade-in {
  animation: fadeIn 0.3s ease-in-out;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(-10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>