<script setup lang="ts">
//import Card from '@/volt/Card.vue';

import { ref } from 'vue';

// Reactive data for the cards
// In a real app, this would likely come from an API call or a store
const cards = ref([
  {
    id: 1,  
    title: "HTML Important Bits",
    topic: "HTML", 
    content: 'Elements, tags, attributes',
    url: "",
    rating: 1, 
  },
  {
    id: 2,  
    title: "HTML and DOM",
    topic: "DOM", 
    content: 'What is DOM?',
    url: "",
    rating: 4,
  },
]);

</script>

<template>
  <main>
    <section>
      <div class="p-5">
        <h1 class="text-3xl font-bold text-center mb-8">Javascript fundamentals</h1>

        <!-- Container with max-width for large screens and centering -->
        <div class="
      max-w-4xl  /* Limit max width on larger screens */
      mx-auto     /* Center the container horizontally */
      grid
      gap-4
      sm:gap-6    /* Slightly larger gap on small screens and up */
      grid-cols-[repeat(auto-fit,minmax(250px,1fr))] /* Responsive grid columns */
    ">
          <div v-for="card in cards" :key="card.id"
            class="bg-white border border-gray-300 rounded-lg p-5 text-center shadow-md">
            <div
              class="flex flex-col h-full p-3 rounded hover:-translate-y-2 transition-transform duration-300 shadow border border-gray-800">
              <div>
                <p class="text-xl text-gray-800 dark:text-gray-100 font-bold">{{ card.title }}</p>
                <p class="text-xl pt-2 text-blue-700 dark:text-gray-400 font-kalam">
                  {{ card.content  }}
                </p>
              </div>
              <div class="mt-auto pt-4 flex">
                <p class="text-gray-500 font-bold dark:text-gray-300">🧰 {{ card.topic }}</p>
                <p class="ml-auto text-gray-500 font-bold dark:text-gray-300">{{ card.rating }} ⭐</p>
              </div>
            </div>
          </div>



        </div>








      </div>
    </section>
  </main>
</template>
