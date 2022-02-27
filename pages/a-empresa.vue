<template>
  <div>
    <div class="bg-gray-100">
      <div class="container mx-auto flex items-center space-x-4 h-10 mb-10">
        <NuxtLink :to="{ name: 'a-empresa' }">A empresa</NuxtLink>
        <NuxtLink to="/servicos">Serviços</NuxtLink>
      </div>
    </div>

    <div>
      <div class="container mx-auto">
        <h1 class="text-lg font-bold">A empresa</h1>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore nesciunt, facilis facere cumque, neque voluptatum magnam nam commodi suscipit beatae assumenda ad quae laborum labore. Minus quibusdam accusamus ducimus voluptas.</p>
      </div>
    </div>
  </div>
</template>
