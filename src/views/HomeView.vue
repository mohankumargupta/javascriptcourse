<script setup lang="ts">
//import Card from '@/volt/Card.vue';

import { ref } from 'vue';

// Reactive data for the cards
// In a real app, this would likely come from an API call or a store
const fundamental_cards = [
  {
    id: 1,
    title: "HTML Important Bits",
    topic: "HTML",
    content: 'Elements, tags, attributes',
    url: "https://mohankumargupta.github.io/javascriptcourse/slides/slides-intro-html",
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
];

const blockly_cards = [
{
    id: 1,
    title: "Hello World Blockly",
    topic: "Blockly",
    content: 'Playground One',
    url: "https://mohankumargupta.github.io/quasaarhelloworld",
    rating: 1,
  },
];

const cards = ref([
  {
    id: 1,
    title: "Javascript fundamentals",
    cards: fundamental_cards,
  },
  {
    id: 2,
    title: "Blockly playgrounds",
    cards: blockly_cards,

  },
])

</script>

<template>
  <main>
    <div v-for="card_section in cards" :key="card_section.id">
      <section>
        <div class="p-5">
          <h1 class="text-3xl font-bold text-center mb-8">{{ card_section.title }}</h1>
          <!-- Container with max-width for large screens and centering -->
          <div class="
      max-w-4xl  /* Limit max width on larger screens */
      mx-auto     /* Center the container horizontally */
      grid
      gap-4
      sm:gap-6    /* Slightly larger gap on small screens and up */
      grid-cols-[repeat(auto-fit,minmax(250px,1fr))] /* Responsive grid columns */
    ">
            <div v-for="card in card_section.cards" :key="card.id"
              class="bg-white border border-gray-300 rounded-lg p-5 text-center shadow-md">
              <a :href="card.url" target="_blank">
              <div
                class="flex flex-col h-full p-3 rounded hover:scale-105 hover:border-blue-700 transition-transform duration-300 shadow border border-gray-800">
                <div>
                  <p class="text-xl text-gray-800  font-bold">{{ card.title }}</p>
                  <p class="text-xl pt-2 text-blue-700 font-kalam">
                    {{ card.content }}
                  </p>
                </div>
                <div class="mt-auto pt-4 flex">
                  <p class="text-gray-500 font-bold">🧰 {{ card.topic }}</p>
                  <p class="ml-auto text-gray-500 font-bold">{{ card.rating }} ⭐</p>
                </div>
              </div>
              </a>
            </div>
          </div>
        </div>
      </section>
    </div>
  </main>
</template>
