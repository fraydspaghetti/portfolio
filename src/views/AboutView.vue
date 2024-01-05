<script setup>
import MainLayout from '../components/MainLayout.vue';

// Page Title of Views
const pageTitle = 'About'
</script>

<template>
  <MainLayout :pageTitle="pageTitle">
    <section class="bg-gray-900 text-white py-8">
      <div class="container mx-auto text-center">
        <p class="text-lg mb-4">
          Greetings!
                </p>
      </div>
    </section>

    <div class="max-w-full w-full bg-white p-8 rounded-lg shadow-md mx-auto mt-8">
      <h2 class="text-3xl font-bold text-cyan-800 mb-6">About Me</h2>

      <form @submit.prevent="submitForm">
        <div class="mb-4">
          <h3 class="text-lg font-semibold text-gray-800 mb-2">
            I'm Christian Kirl D. Tago, a passionate and aspiring programmer currently pursuing a Bachelor's degree in Information Technology (BSIT) at Cordova Public College. I thrive on turning complex problems into elegant, efficient, and user-friendly solutions.

          </h3>
        </div>
      </form>
    </div>
  </MainLayout>
</template>
