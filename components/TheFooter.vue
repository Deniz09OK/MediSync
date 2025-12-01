<template>
  <footer class="bg-gradient-to-br from-sky-50 to-emerald-50 border-t border-sky-100 mt-20">
    <div class="container mx-auto px-4 lg:px-8 py-12">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
        <!-- Logo et Description -->
        <div class="col-span-1 md:col-span-2">
          <div class="flex items-center space-x-3 mb-4">
            <div class="w-10 h-10 bg-gradient-to-br from-sky-400 to-emerald-400 rounded-xl flex items-center justify-center">
              <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
              </svg>
            </div>
            <span class="text-xl font-bold bg-gradient-to-r from-sky-600 to-emerald-600 bg-clip-text text-transparent">
              MediSync
            </span>
          </div>
            <p class="text-gray-600 max-w-md text-sm leading-relaxed mb-4">
              La première plateforme de santé connectée qui relie l'observance médicamenteuse au vécu réel du patient pour une prise en charge véritablement personnalisée.
            </p>
            <div class="flex items-center space-x-3">
              <a 
                href="https://www.linkedin.com/in/deniz-ok" 
                target="_blank"
              rel="noopener noreferrer"
              class="w-10 h-10 rounded-full bg-white border border-sky-200 flex items-center justify-center text-sky-600 hover:bg-sky-50 hover:border-sky-300 transition-all"
              aria-label="LinkedIn - Deniz"
            >
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
              </svg>
            </a>
            <a 
              href="https://www.linkedin.com/in/claire-estelle-zobo/" 
              target="_blank"
              rel="noopener noreferrer"
              class="w-10 h-10 rounded-full bg-white border border-sky-200 flex items-center justify-center text-sky-600 hover:bg-sky-50 hover:border-sky-300 transition-all"
              aria-label="LinkedIn - Claire-Estelle"
            >
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
              </svg>
            </a>
            <a 
              href="https://www.linkedin.com/in/michel-banckaert-54-devweb/" 
              target="_blank"
              rel="noopener noreferrer"
              class="w-10 h-10 rounded-full bg-white border border-sky-200 flex items-center justify-center text-sky-600 hover:bg-sky-50 hover:border-sky-300 transition-all"
              aria-label="LinkedIn - Michel"
            >
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
              </svg>
            </a>
          </div>
        </div>

        <!-- Navigation -->
        <div>
          <h3 class="font-semibold text-gray-800 mb-4">Navigation</h3>
          <ul class="space-y-2">
            <li v-for="link in navigation" :key="link.to">
              <NuxtLink 
                :to="link.to" 
                class="text-gray-600 hover:text-sky-600 text-sm transition-colors"
              >
                {{ link.label }}
              </NuxtLink>
            </li>
          </ul>
        </div>

        <!-- Contact -->
        <div>
          <h3 class="font-semibold text-gray-800 mb-4">L'équipe</h3>
          <ul class="space-y-4 text-sm text-gray-600">
            <li class="flex items-center">
              <span>Deniz OK</span>
            </li>
            <li class="flex items-center">
              <span>Claire-Estelle Zobo</span>
            </li>
            <li class="flex items-center">
              <span>Michel Banckaert</span>
            </li>
          </ul>
        </div>
      </div>
    </div>
    </footer>
</template>

<script setup>
const navigation = [
  { label: 'Accueil', to: '/' },
  { label: 'Le Projet', to: '/projet' },
  { label: 'Fonctionnalités', to: '/fonctionnalites' },
  { label: 'L\'Équipe', to: '/equipe' },
  { label: 'Contact', to: '/contact' }
]
</script>
