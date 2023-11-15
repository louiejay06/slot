<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
import Card from '@/Components/Card.vue';
</script>

<template>
  <Head title="Dashboard" />

  <AuthenticatedLayout>
    <template #header>
      <h2 class="font-semibold text-xl text-gray-800 leading-tight">Dashboard</h2>
    </template>

    <div class="py-12">
      <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
        <div class="">
          <!-- First Card - Lorem -->
          <Card class="border shadow-sm mb-4 rounded-lg">
            <template v-slot:header>
                <h3 class="text-2xl font-semibold text-black">Lorem ipsum dolor sit amet</h3>
            </template>
            <template v-slot:body>
              <div class="mb-2">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis optio amet sint suscipit voluptatibus doloribus nulla corrupti provident tempora delectus perferendis, earum repellendus aperiam cupiditate, commodi necessitatibus tempore impedit ipsum? Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nemo ducimus unde officiis, totam beatae fuga sed eos esse quo dolores? Soluta, quae at? Odit expedita aspernatur, sint cum laborum accusamus.
              </div>
            </template>
            <template v-slot:footer>
              <button type="submit" class="px-4 py-2 rounded-lg bg-blue-600 text-sm font-medium text-white">Go to</button>
            </template>
          </Card>

          <Card class="border shadow-sm mb-4 rounded-lg max-w-xl">
            <template v-slot:header>
                <p class="text-lg font-normal text-gray-500">Tailwind v3.1.4</p>
                <h5 class="text-2xl font-semibold text-gray-900">Product Card</h5>
            </template>
            <template v-slot:body>
              <div class="mb-2 mt-2">
                The Product Card component is an easy way to display content like product intros. This Product card component displaying featured image, title, price, description, add to cart button and call to action button.
              </div>
            </template>
            <template v-slot:footer>
              <div class="flex items-center space-x-4">
                <div class="inline-flex items-center">
                    Category: &nbsp;
                    <button type="submit" class="px-4 py-2 rounded-lg bg-blue-600 text-sm font-medium text-white">Ecommerce</button>
                </div>
                <div class="inline-flex items-center">
                    Tags: &nbsp;
                    <button type="submit" class="px-4 py-2 rounded-lg bg-green-600 text-sm font-medium text-white">card</button>
                    <button type="submit" class="px-4 py-2 rounded-lg bg-green-600 text-sm font-medium text-white ml-2">product</button>
                </div>
              </div>
            </template>
          </Card>

          <Card class="border shadow-sm mb-4 rounded-lg max-w-sm">
            <template v-slot:header>
                <img src="https://images.unsplash.com/photo-1600185365483-26d7a4cc7519?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8OHx8c25lYWtlcnxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60" alt="">
                <h5 class="text-2xl font-semibold text-gray-900 mt-4">Nike Air MX Super 2500 - Red</h5>
            </template>
            <template v-slot:body>
                <div class="flex items-center mt-2.5 mb-5">
            <div class="flex items-center space-x-1 rtl:space-x-reverse">
                <svg class="w-4 h-4 text-yellow-300" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 22 20">
                    <path d="M20.924 7.625a1.523 1.523 0 0 0-1.238-1.044l-5.051-.734-2.259-4.577a1.534 1.534 0 0 0-2.752 0L7.365 5.847l-5.051.734A1.535 1.535 0 0 0 1.463 9.2l3.656 3.563-.863 5.031a1.532 1.532 0 0 0 2.226 1.616L11 17.033l4.518 2.375a1.534 1.534 0 0 0 2.226-1.617l-.863-5.03L20.537 9.2a1.523 1.523 0 0 0 .387-1.575Z"/>
                </svg>
                <svg class="w-4 h-4 text-yellow-300" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 22 20">
                    <path d="M20.924 7.625a1.523 1.523 0 0 0-1.238-1.044l-5.051-.734-2.259-4.577a1.534 1.534 0 0 0-2.752 0L7.365 5.847l-5.051.734A1.535 1.535 0 0 0 1.463 9.2l3.656 3.563-.863 5.031a1.532 1.532 0 0 0 2.226 1.616L11 17.033l4.518 2.375a1.534 1.534 0 0 0 2.226-1.617l-.863-5.03L20.537 9.2a1.523 1.523 0 0 0 .387-1.575Z"/>
                </svg>
                <svg class="w-4 h-4 text-yellow-300" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 22 20">
                    <path d="M20.924 7.625a1.523 1.523 0 0 0-1.238-1.044l-5.051-.734-2.259-4.577a1.534 1.534 0 0 0-2.752 0L7.365 5.847l-5.051.734A1.535 1.535 0 0 0 1.463 9.2l3.656 3.563-.863 5.031a1.532 1.532 0 0 0 2.226 1.616L11 17.033l4.518 2.375a1.534 1.534 0 0 0 2.226-1.617l-.863-5.03L20.537 9.2a1.523 1.523 0 0 0 .387-1.575Z"/>
                </svg>
                <svg class="w-4 h-4 text-yellow-300" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 22 20">
                    <path d="M20.924 7.625a1.523 1.523 0 0 0-1.238-1.044l-5.051-.734-2.259-4.577a1.534 1.534 0 0 0-2.752 0L7.365 5.847l-5.051.734A1.535 1.535 0 0 0 1.463 9.2l3.656 3.563-.863 5.031a1.532 1.532 0 0 0 2.226 1.616L11 17.033l4.518 2.375a1.534 1.534 0 0 0 2.226-1.617l-.863-5.03L20.537 9.2a1.523 1.523 0 0 0 .387-1.575Z"/>
                </svg>
                <svg class="w-4 h-4 text-gray-200 dark:text-gray-600" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 22 20">
                    <path d="M20.924 7.625a1.523 1.523 0 0 0-1.238-1.044l-5.051-.734-2.259-4.577a1.534 1.534 0 0 0-2.752 0L7.365 5.847l-5.051.734A1.535 1.535 0 0 0 1.463 9.2l3.656 3.563-.863 5.031a1.532 1.532 0 0 0 2.226 1.616L11 17.033l4.518 2.375a1.534 1.534 0 0 0 2.226-1.617l-.863-5.03L20.537 9.2a1.523 1.523 0 0 0 .387-1.575Z"/>
                </svg>
            </div>
            <span class="bg-blue-100 text-blue-800 text-xs font-semibold px-2.5 py-0.5 rounded dark:bg-blue-200 dark:text-blue-800 ms-3">5.0</span>
        </div>
            </template>
            <template v-slot:footer>
                <div class="flex items-center justify-between">
                    <span class="text-3xl font-bold text-gray-900 dark:text-white">$599</span>
                    <a href="#" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Add to cart</a>
                </div>
            </template>
          </Card>

        </div>
      </div>
    </div>
  </AuthenticatedLayout>
</template>

<style scoped>
.lorem-card,
.image-card,
.button-card {
  border-radius: 0.5rem;
  box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);
  overflow: hidden;
}

.card-header {
  padding: 1rem;
}

.card-body {
  padding: 1rem;
}

.card-footer {
  padding: 1rem;
}
</style>
