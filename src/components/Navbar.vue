<template>
    <header class="bg-white shadow h-16 flex justify-between border-b-2 border-orange-500 items-stretch">
      <router-link
        :to="{ name: 'home' }"
        class="inline-flex items-center h-full text-lg px-5 text-orange-500 font-bold"
      >
        Home
      </router-link>
      <div class="flex items-center gap-1">
        <router-link
          :to="{ name: 'byName' }"
          class="inline-flex items-center px-2 h-full transition-colors hover:bg-orange-500 hover:text-white"
        >
          Search Meals
        </router-link>
        <router-link
          :to="{ name: 'byLetter' }"
          class="inline-flex items-center px-2 h-full transition-colors hover:bg-orange-500 hover:text-white"
        >
          Meals By Letter
        </router-link>
        <router-link
          :to="{ name: 'ingredients' }"
          class="inline-flex items-center px-2 h-full transition-colors hover:bg-orange-500 hover:text-white"
        >
          Meals By Ingredients
        </router-link>
      </div>
    </header>
  </template>