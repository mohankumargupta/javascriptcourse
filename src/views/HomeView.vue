<script setup lang="ts">
import Card from '@/volt/Card.vue';

import { ref } from 'vue';

// Reactive data for the cards
// In a real app, this would likely come from an API call or a store
const cards = ref([
  { id: 1, content: 'Card 1' },
  { id: 2, content: 'Card 2' },
  { id: 3, content: 'Card 3' },
  { id: 4, content: 'Card 4' },
  { id: 5, content: 'Card 5' },
  { id: 6, content: 'Card 6' },
  { id: 7, content: 'Card 7' },
  { id: 8, content: 'Card 8' },
  { id: 9, content: 'Card 9 (Longer Content Example)' },
  { id: 10, content: 'Card 10' },
  ]);

</script>

<template>
  <main>
    <h1 class="text-3xl font-bold underline">
      Hello world!
    </h1>
    <Card>
      <template #title>
        title
      </template>
      <template #content>
      content
      </template>
    </Card>

    <div class="p-5">
    <h1 class="text-3xl font-bold text-center mb-8">Responsive Card Grid (Vue 3 + Tailwind)</h1>

    <!-- Container with max-width for large screens and centering -->
    <div class="
      max-w-4xl  /* Limit max width on larger screens */
      mx-auto     /* Center the container horizontally */
      grid
      gap-4
      sm:gap-6    /* Slightly larger gap on small screens and up */
      grid-cols-[repeat(auto-fit,minmax(250px,1fr))] /* Responsive grid columns */
    ">
      <!-- Loop through cards data -->
      <div
        v-for="card in cards"
        :key="card.id"
        class="bg-white border border-gray-300 rounded-lg p-5 text-center shadow-md"
      >
        {{ card.content }}
      </div>
    </div>

    <div class="flex flex-col h-full p-3 rounded hover:-translate-y-2 transition-transform duration-300 shadow border border-gray-800"><div><p class="text-xl text-gray-800 dark:text-gray-100 font-bold">daisy-rsx</p><p class="text-base pt-2 text-gray-700 dark:text-gray-400">A Dioxus version of the Daisy UI components.</p></div><div class="mt-auto pt-4 flex"><p class="text-gray-500 font-bold dark:text-gray-300">🧰 Util</p><p class="ml-auto text-gray-500 font-bold dark:text-gray-300">88 ⭐</p></div></div>

  </div>

  </main>
</template>
