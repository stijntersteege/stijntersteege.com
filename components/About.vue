<template>
  <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl">
    <div class="grid gap-5 row-gap-10 lg:grid-cols-2">
      <div class="flex flex-col justify-center">
        <div class="max-w-xl mb-6">
          <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
            I design and code digital<br class="hidden md:block"/>
            products, and
            <span class="relative px-1">
            <div class="absolute inset-x-0 bottom-0 h-3 transform -skew-x-12 bg-gray-300"></div>
            <span class="relative inline-block text-blue-accent-400">I love what I do</span>
          </span>
          </h2>
          <p class="text-base text-gray-700 md:text-lg">
            My journey started about {{ new Date().getFullYear() - 2016 }} years ago, in which I've collaborated with
            talented people and have done great projects for startups and companies with over 250+ employees.
          </p>
        </div>
        <p class="mb-4 text-sm font-bold tracking-widest uppercase">TL;DR</p>
        <div class="space-y-3 sm:gap-2">
          <ul class="space-y-3">
            <li class="flex">
            <span class="mr-1">
              <svg class="w-5 h-5 mt-px text-blue-accent-400" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="4" stroke-linecap="round" stroke-linejoin="round" fill="none"
                         points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </span>
              I started out as a kid building my own computer 💾
            </li>
            <li class="flex">
            <span class="mr-1">
              <svg class="w-5 h-5 mt-px text-blue-accent-400" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="4" stroke-linecap="round" stroke-linejoin="round" fill="none"
                         points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </span>
              I enjoy bringing ideas to life with software 💻
            </li>
            <li class="flex">
            <span class="mr-1">
              <svg class="w-5 h-5 mt-px text-blue-accent-400" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="4" stroke-linecap="round" stroke-linejoin="round" fill="none"
                         points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </span>
              The list of destinations on my travel wishlist is too long to mention ✈
            </li>
            <li class="flex">
            <span class="mr-1">
              <svg class="w-5 h-5 mt-px text-blue-accent-400" stroke="currentColor" viewBox="0 0 52 52">
                <polygon stroke-width="4" stroke-linecap="round" stroke-linejoin="round" fill="none"
                         points="29 13 14 29 25 29 23 39 38 23 27 23"></polygon>
              </svg>
            </span>
              Off the clock, you will most likely find me working out at the gym 💪
            </li>
          </ul>
        </div>
      </div>
      <div>
        <img class="object-cover w-full h-full rounded shadow-lg" src="stijntersteege.jpg" alt="Stijn ter Steege"/>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "About"
}
</script>

<style scoped>

</style>