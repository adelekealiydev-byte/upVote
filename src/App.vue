<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import './assets/seed.js'
</script>

<template>
  <h1 class="mb-6 text-2xl font-bold text-gray-800 text-center mt-12">UpVote!</h1>
  <div class="px-6 py-6 w-full max-w-4xl mx-auto">
  <article class="flex items-start border border-gray-200 sm:px-12 px-6 py-6 rounded-lg shadow-sm">
    <!-- Left Figure -->
    <figure class="mr-4 shrink-0">
      <img
        class="h-16 w-16 rounded object-cover"
        src="/images/submissions/vue.png"
        alt="vue.js"
      />
    </figure>

    <!-- Main Content -->
    <div class="min-w-0 flex-1">
      <div>
        <p class="text-gray-700">
          <strong>
            <a href="#" class="font-bold text-blue-500 hover:underline">Vue js</a>
            <span class="ml-2 inline-flex items-center rounded bg-gray-100 px-2 py-0.5 text-xs font-normal text-gray-600">
              #4
            </span>
          </strong>
          <br />
          Vue.js is a progressive JavaScript framework for building user interfaces.
          <br />
          <small class="inline-flex items-center gap-1 text-xs text-gray-500">
            Submitted by:
            <img
              class="inline-block h-6 w-6 rounded-full align-middle"
              src="/images/avatars/profile00.avif"
              alt="Avatar"
            />
          </small>
        </p>
      </div>
    </div>

    <!-- Right Column (Votes) -->
    <div class="ml-4 shrink-0">
      <span class="inline-flex cursor-pointer items-center gap-1 text-sm text-blue-500">
        <i class="fa fa-chevron-up"></i>
        <strong class="font-bold text-blue-500">10</strong>
      </span>
    </div>
  </article>
</div>
</template>



<!-- <template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>


  <RouterView />
</template> -->

<!-- <style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style> -->
