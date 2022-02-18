<template>
  <div>
    <navigation-section/>

    <div class="mb-16">
      <div>
        <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
          <div class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12">
            <h2
              class="max-w-lg mb-6 font-sans text-3xl font-bold leading-none tracking-tight text-gray-900 sm:text-4xl md:mx-auto">
            <span class="relative inline-block">
              <svg viewBox="0 0 52 24" fill="currentColor"
                   class="absolute top-0 left-0 z-0 hidden w-32 -mt-8 -ml-20 text-gray-400 lg:w-32 lg:-ml-28 lg:-mt-10 sm:block">
                <defs>
                  <pattern id="dc223fcc-6d72-4ebc-b4ef-abe121034d6e" x="0" y="0" width=".135" height=".30">
                    <circle cx="1" cy="1" r=".7"></circle>
                  </pattern>
                </defs>
                <rect fill="url(#dc223fcc-6d72-4ebc-b4ef-abe121034d6e)" width="52" height="24"></rect>
              </svg>
              <span class="relative">Thanks</span>
            </span>
              for taking the time to reach out. How may I help you?
            </h2>
            <p class="text-base text-gray-700 md:text-lg">
              Feel free to contact me at any time.
            </p>
            <p class="text-sm text-gray-500">
              {{ new Date().toLocaleString('en-us') }}. (Central European Summer Time (CEST), UTC +2)
            </p>
          </div>
        </div>
      </div>
      <div class="relative px-4 sm:px-0">
        <div class="absolute inset-0 h-1/2"></div>
        <div
          class="relative grid mx-auto overflow-hidden bg-white divide-y rounded shadow sm:divide-y-0 sm:divide-x sm:max-w-screen-sm sm:grid-cols-2 lg:max-w-screen-md">
          <div class="inline-block p-8 text-center">
            <div class="flex items-center justify-center w-12 h-12 mx-auto mb-4 rounded-full bg-indigo-50">
              <svg xmlns="http://www.w3.org/2000/svg" class="text-deep-purple-accent-400" width="24" height="24"
                   viewBox="0 0 24 24" fill="currentColor">
                <path
                  d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/>
              </svg>
            </div>
            <p class="font-bold tracking-wide text-gray-800">Chat with me</p>
            <a href="https://wa.me/31611676634"
               class="inline-flex items-center text-sm font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800">
              Open WhatsApp
            </a>
          </div>
          <div class="inline-block p-8 text-center">
            <div class="flex items-center justify-center w-12 h-12 mx-auto mb-4 rounded-full bg-indigo-50">
              <svg xmlns="http://www.w3.org/2000/svg" class="text-deep-purple-accent-400" width="24" height="24"
                   viewBox="0 0 24 24" fill="currentColor">
                <path
                  d="M0 12l11 3.1 7-8.1-8.156 5.672-4.312-1.202 15.362-7.68-3.974 14.57-3.75-3.339-2.17 2.925v-.769l-2-.56v7.383l4.473-6.031 4.527 4.031 6-22z"/>
              </svg>
            </div>
            <p class="font-bold tracking-wide text-gray-800">Email me</p>
            <a href="mailto:mail@stijntersteege.com"
               class="inline-flex items-center text-sm font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800">
              mail@stijntersteege.com
            </a>
          </div>
        </div>
      </div>
    </div>

    <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
      <div class="flex flex-col max-w-screen-lg overflow-hidden bg-white border rounded shadow-sm lg:flex-row sm:mx-auto">
        <div class="relative lg:w-1/2">
          <img
            src="https://images.pexels.com/photos/160107/pexels-photo-160107.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260"
            alt="Macbook with code" class="object-cover w-full lg:absolute h-80 lg:h-full"/>
          <svg class="absolute top-0 right-0 hidden h-full text-white lg:inline-block" viewBox="0 0 20 104"
               fill="currentColor">
            <polygon points="17.3036738 5.68434189e-14 20 5.68434189e-14 20 104 0.824555778 104"></polygon>
          </svg>
        </div>
        <div class="flex flex-col justify-center p-8 bg-white lg:p-16 lg:pl-10 lg:w-1/2">
          <div>
            <p
              class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-accent-400">
              Let's collaborate
            </p>
          </div>
          <h5 class="mb-3 text-3xl font-extrabold leading-none sm:text-4xl">
            Start the conversation
          </h5>
          <p class="mb-5 text-gray-800">
            Interested in working together? Please reach out to me. I’ll buy the coffee (or beer) if we are meeting in
            real life.
          </p>
          <div class="flex items-center">
            <NuxtLink
              to="/"
              class="inline-flex items-center justify-center h-12 px-6 mr-6 font-medium tracking-wide text-white transition duration-200 rounded shadow-md bg-deep-purple-accent-400 hover:bg-deep-purple-accent-700 focus:shadow-outline focus:outline-none">
              About me
            </NuxtLink>
            <NuxtLink to="/services"
                      class="inline-flex items-center font-semibold transition-colors duration-200 text-deep-purple-accent-400 hover:text-deep-purple-800">
              View services
              <svg class="inline-block w-3 ml-2" fill="currentColor" viewBox="0 0 12 12">
                <path
                  d="M9.707,5.293l-5-5A1,1,0,0,0,3.293,1.707L7.586,6,3.293,10.293a1,1,0,1,0,1.414,1.414l5-5A1,1,0,0,0,9.707,5.293Z"></path>
              </svg>
            </NuxtLink>
          </div>
        </div>
      </div>
    </div>

    <footer-section/>
  </div>
</template>

<script>
import Navigation from "../components/NavigationLight";
import Footer from "../components/Footer";

export default {
  components: {
    'navigation-section': Navigation,
    'footer-section': Footer,
  }
}
</script>
