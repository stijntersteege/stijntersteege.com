<template>
  <div class="relative mt-16 bg-deep-purple-accent-400">
    <svg class="absolute top-0 w-full h-6 -mt-5 sm:-mt-10 sm:h-16 text-deep-purple-accent-400"
         preserveAspectRatio="none" viewBox="0 0 1440 54">
      <path fill="currentColor"
            d="M0 22L120 16.7C240 11 480 1.00001 720 0.700012C960 1.00001 1200 11 1320 16.7L1440 22V54H1320C1200 54 960 54 720 54C480 54 240 54 120 54H0V22Z"></path>
    </svg>
    <div class="px-4 pt-12 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8">
      <div class="grid gap-10 row-gap-6 mb-8 sm:grid-cols-2 lg:grid-cols-4">
        <div class="sm:col-span-2">
          <NuxtLink to="/" aria-label="Go home" title="Stijn ter Steege" class="inline-flex items-center">
            <span class="text-xl font-bold tracking-wide text-gray-100 uppercase">Stijn ter Steege</span>
          </NuxtLink>
          <div class="mt-6 lg:max-w-sm">
            <p class="text-sm text-deep-purple-50">
              I design and develop digital products to help companies grow. As a full stack developer I build intuitive
              and dynamic apps and websites to ensure an optimal user experience 🚀
            </p>
          </div>
        </div>
        <div class="space-y-2 text-sm">
          <p class="text-base font-bold tracking-wide text-teal-accent-400">Information</p>
          <div class="flex">
            <p class="mr-1 text-deep-purple-50">Email:</p>
            <a href="mailto:info@lorem.mail" aria-label="Email" title="Email"
               class="transition-colors duration-300 text-deep-purple-50 hover:text-teal-accent-400">mail@stijntersteege.com</a>
          </div>
          <div class="flex">
            <p class="mr-1 text-deep-purple-50">Chamber of Commerce:</p>
            <p class="text-deep-purple-50">67721540</p>
          </div>
          <div class="flex">
            <p class="mr-1 text-deep-purple-50">VAT:</p>
            <p class="text-deep-purple-50">NL002410763B69</p>
          </div>
        </div>
        <div>
          <span class="text-base font-bold tracking-wide text-teal-accent-400">Let's connect</span>
          <div class="flex items-center mt-1 space-x-3">
            <a href="https://www.linkedin.com/in/stijntersteege/?locale=en_US"
               class="transition-colors duration-300 text-deep-purple-100 hover:text-teal-accent-400">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="h-6">
                <path
                  d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/>
              </svg>
            </a>
            <a href="https://github.com/stijntersteege" class="transition-colors duration-300 text-deep-purple-100 hover:text-teal-accent-400">
               <svg fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" class="h-7 w-7">
                <path fill-rule="evenodd" 
                  d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd"></path>
               </svg>
            </a>
          </div>
        </div>
      </div>
      <div class="flex flex-col-reverse justify-between pt-5 pb-10 border-t lg:flex-row">
        <p class="text-sm text-deep-purple-100">
          © 2017 - {{ new Date().getFullYear() }} <span class="font-bold">Stijn ter Steege</span>. All rights reserved.
          Prices excluding tax.
        </p>
        <ul class="flex flex-col mb-3 space-y-2 lg:mb-0 sm:space-y-0 sm:space-x-5 sm:flex-row">
          <li>
            <a href="/cookie-policy.pdf"
               class="text-sm transition-colors duration-300 text-deep-purple-100 hover:text-teal-accent-400">Cookie
              Policy</a>
          </li>
          <li>
            <a href="/privacy-policy.pdf"
               class="text-sm transition-colors duration-300 text-deep-purple-100 hover:text-teal-accent-400">Privacy
              Policy</a>
          </li>
          <li>
            <a href="/terms-conditions.pdf"
               class="text-sm transition-colors duration-300 text-deep-purple-100 hover:text-teal-accent-400">Terms
              &amp; Conditions</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
