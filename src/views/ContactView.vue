<script setup> const FacebookLink = 'https://www.facebook.com/loki.mendez.33483903/';
import MainLayout from '../components/MainLayout.vue';

// Page Title of Views
const pageTitle = 'Contact'
</script>

<template>
  <MainLayout :pageTitle="pageTitle">
    <section class="bg-gray-900 text-white py-8">
      <div class="container mx-auto text-center">
        <p class="text-lg mb-4">
          Stay connected with me and reach me through my socials!
        </p>
      </div>
    </section>

    <div class="max-w-full w-full bg-white p-8 rounded-lg shadow-md mx-auto mt-8">
      <h2 class="text-3xl font-bold text-cyan-800 mb-6">Get in Touch</h2>

      <form @submit.prevent="submitForm">
        <div class="mb-4">
          <div>
            <h3 class="text-lg font-semibold text-gray-800 mb-2">My Facebook:</h3>
            <a href="https://www.facebook.com/FraydSpaghetti" target="_blank" class="text-blue-500 underline hover:text-blue-700">https://www.facebook.com/FraydSpaghetti</a>
          </div>

          <div class="mt-4">
            <h3 class="text-lg font-semibold text-gray-800 mb-2">My Contact Number:</h3>
            <p class="text-gray-600">09503398538</p>
          </div>

          
        </div>
      </form>
    </div>
  </MainLayout>
</template>
