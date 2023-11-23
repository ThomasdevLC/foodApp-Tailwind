<template>
  <div class="font-body">
    <nav>
      <div>
        <h1 class="font-bold uppercase p-4 border-t border-gray-100">
          <a href="/">Food Ninja</a>
        </h1>
      </div>
      <ul>
        <li class="text-gray-700 font-bold">
          <a href="#">
            <span>Home</span>
          </a>
        </li>
        <li>
          <a href="#">
            <span>About</span>
          </a>
        </li>
        <li>
          <a href="#">
            <span>Contact</span>
          </a>
        </li>
      </ul>
    </nav>
  </div>

  <main class="px-16 py-6">
    <div class="flex justify-end">
      <a href="#" class="text-primary font-body">Log in</a>
      <a href="#" class="text-primary font-body ml-3">Sign up</a>
    </div>

    <div class="flex justify-center items-end">
      <div class="bg-red-500 h-4 w-6"></div>
      <div class="bg-blue-500 h-8 w-6"></div>
      <div class="bg-green-500 h-12 w-6"></div>
    </div>

    <header>
      <h2 class="text-gray-700 text-6xl font-semibold">Recipes</h2>
      <h3 class="text-2xl font-semibold">For Ninjas</h3>
    </header>

    <div>
      <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">Latest Recipes</h4>

      <div class="mt-8">
        <!-- cards go here -->
        <div>
          <img src="../assets/images/stew.jpg" alt="stew" />
          <div>
            <span>5 Bean Chili Stew</span>
            <span>Recipe by Mario</span>
          </div>
        </div>
      </div>

      <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">Most Popular</h4>

      <div class="mt-8">
        <!-- cards go here -->
      </div>
    </div>

    <div class="flex justify-center">
      <div class="bg-secondary-100 text-secondary-200">Load more</div>
    </div>
  </main>
</template>

<script setup></script>

<style lang="scss" scoped></style>
