<template>
  <footer>
    <div class="px-4 sm:px-6 lg:px-8 pt-12 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl">
      <div class="flex flex-col mb-6 lg:flex-row md:mb-10">
        <div class="lg:w-1/2">
          <h2 class="max-w-md mb-6 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none xl:max-w-lg">
            Interested in working with me? We should queue up a chat.
          </h2>
        </div>
        <div class="lg:w-1/2">
          <p class="text-base text-gray-700 md:text-lg">
            Feel free to send me a good old-fashioned <a href="mailto:mail@stijntersteege.com"
                                                         class="underline text-blue-400 hover:text-blue-700">email</a>
            or slide into my DMs on <a href="https://www.linkedin.com/in/stijntersteege/?locale=en_US"
                                       class="underline text-blue-400 hover:text-blue-700">LinkedIn</a>. I’ll buy the
            coffee ☕.
          </p>
          <p class="mt-3 text-sm text-gray-700">
            I'm registered with the Chamber of Commerce (KvK) in The Netherlands under ID 67721540. My VAT number is
            NL002410763B69.
          </p>
        </div>
      </div>
    </div>
    <div class="
        max-w-7xl
        mx-auto
        py-12
        px-4
        sm:px-6
        md:flex md:items-center md:justify-between
        lg:px-8">
      <div class="flex justify-center space-x-2 md:order-2">
        <a href="https://www.linkedin.com/in/stijntersteege/?locale=en_US"
           class="text-gray-500 hover:text-gray-600">
          <span class="sr-only">LinkedIn</span>
          <svg fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="h-6 w-5">
            <path
                d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/>
          </svg>
        </a>
        <a href="https://github.com/stijntersteege"
           class="text-gray-500 hover:text-gray-600">
          <span class="sr-only">GitHub</span>
          <svg fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6">
            <path fill-rule="evenodd"
                  d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                  clip-rule="evenodd"></path>
          </svg>
        </a>
      </div>
      <div class="mt-8 md:mt-0 md:order-1">
        <p class="text-center text-base text-gray-600">© {{ new Date().getFullYear() }} Stijn ter Steege</p>
      </div>
    </div>
  </footer>
</template>
