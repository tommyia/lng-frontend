<!-- Please remove this file from your project -->
<template>
  <div class="overflow-x-hidden sm:overflow-x-clip">
    <div class="bg-white">
      <header class="bg-white fixed inset-x-0 top-0 z-50">
        <nav
          class="relative mx-auto max-w-7xl px-6 lg:px-0 flex items-center justify-between p-6"
        >
          <div class="flex lg:flex-1">
            <a href="/" class="-m-1.5 p-1.5 flex space-x-2 items-center">
              <span class="sr-only">Your Company</span>
              <img src="lgn.png" class="w-auto h-10">
            </a>
          </div>
          <div class="flex lg:hidden">
            <button
              type="button"
              class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-gray-700"
              @click="toggleMenu"
            >
              <span class="sr-only">Open main menu</span>
              <svg
                class="h-6 w-6"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
                />
              </svg>
            </button>
          </div>
          <div
            class="hidden lg:flex lg:gap-x-12"
          >
            <a
              href="#aboutus"
              class="text-sm font-semibold leading-6 text-gray-900"
            >{{ $t('menu_about_us') }}</a>
            <a
              href="#service"
              class="text-sm font-semibold leading-6 text-gray-900"
            >{{ $t('menu_service') }}</a>
            <a
              href="#why"
              class="text-sm font-semibold leading-6 text-gray-900"
            >{{ $t('menu_why_lgn') }}</a>
            <a
              href="#teams"
              class="text-sm font-semibold leading-6 text-gray-900"
            >{{ $t('menu_teams') }}</a>
            <a
              href="#client"
              class="text-sm font-semibold leading-6 text-gray-900"
            >{{ $t('menu_client') }}</a>
          </div>
          <div class="hidden lg:flex lg:flex-1 lg:justify-end">
            <div class="relative mr-2">
              <button
                type="button"
                class="relative p-2 hover:text-gray-800 text-left cursor-pointer focus:outline-none sm:text-sm lg:hover:bg-gray-100 ml-2"
                aria-expanded="false"
                aria-haspopup="true"
                :aria-label="getLangShortName($i18n.locale)"
                @click="() => { showLanguageSwitch = !showLanguageSwitch; showMenu = false; showProfile = false; showMobileSearch = false; searchState = 'init'; showSubMenu = false }"
              >
                <span class="flex items-center">
                  <img :src="getLangImage($i18n.locale)" width="40" height="40" alt="Language Flag" class="flex-shrink-0 w-6 h-6 rounded-full">
                  <span class="ml-3 font-semibold truncate block text-xs">
                    {{ getLangShortName($i18n.locale) }}
                  </span>
                </span>
              </button>

              <ul
                v-on-clickaway="() => showLanguageSwitch = false"
                class="absolute right-0 z-50 py-1 mt-1 overflow-auto text-base bg-white rounded-md shadow-lg w-28 max-h-56 ring-1 ring-black ring-opacity-5 focus:outline-none sm:text-sm"
                tabindex="-1"
                role="listbox"
                aria-labelledby="listbox-label"
                aria-activedescendant="listbox-option-3"
                :class="showLanguageSwitch ? 'absolute' : 'hidden'"
              >
                <li
                  class="relative py-2 pl-3 text-gray-900 cursor-pointer select-none pr-9 hover:bg-gray-100"
                  role="option"
                  @click="switchLanguage('id')"
                >
                  <div class="flex items-center">
                    <img
                      src="~/assets/images/id.svg"
                      width="40"
                      height="40"
                      alt="Language Flag"
                      class="flex-shrink-0 w-4 h-4 rounded-full"
                    >
                    <span class="block ml-3 truncate">
                      ID
                    </span>
                  </div>
                </li>
                <li
                  class="relative py-2 pl-3 text-gray-900 cursor-pointer select-none pr-9 hover:bg-gray-100"
                  role="option"
                  @click="switchLanguage('en')"
                >
                  <div class="flex items-center">
                    <img
                      src="~/assets/images/en.svg"
                      width="40"
                      height="40"
                      alt="Language Flag"
                      class="flex-shrink-0 w-4 h-4 rounded-full"
                    >
                    <span class="block ml-3 truncate">
                      EN
                    </span>
                  </div>
                </li>
              </ul>
            </div>
            <a
              href="#contactus"
              class="text-sm font-semibold leading-6 text-white bg-[#ff6600] px-4 py-2"
            >Contact Us <span aria-hidden="true">&rarr;</span></a>
          </div>
          <div class="absolute bottom-0 w-full h-0.5 bg-[#ff6600] sm:hidden" style="background: linear-gradient(90deg, rgba(255, 102, 0, 0) 0%, rgba(255, 102, 0, 0.52) 51.5%, rgba(255, 102, 0, 0) 100%); opacity: 1;" />
        </nav>
        <!-- Mobile menu, show/hide based on menu open state. -->
        <div v-if="isMenuOpen" class="" role="dialog" aria-modal="true">
          <!-- Background backdrop, show/hide based on slide-over state. -->
          <div
            class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10"
          >
            <div class="flex items-center justify-between">
              <a href="/" class="-m-1.5 p-1.5" @click="toggleMenu">
                <span class="sr-only">Your Company</span>
                <img src="lgn.png" class="w-auto h-10">
              </a>
              <button
                type="button"
                class="-m-2.5 rounded-md p-2.5 text-gray-700"
                @click="toggleMenu"
              >
                <span class="sr-only">Close menu</span>
                <svg
                  class="h-6 w-6"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M6 18L18 6M6 6l12 12"
                  />
                </svg>
              </button>
            </div>
            <div class="mt-6 flow-root">
              <div class="-my-6 divide-y divide-gray-500/10">
                <div class="space-y-2 py-6">
                  <a
                    href="#aboutus"
                    class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                    @click="toggleMenu"
                  >
                    {{ $t('menu_about_us') }}
                  </a>
                  <a
                    href="#service"
                    class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                    @click="toggleMenu"
                  >
                    {{ $t('menu_service') }}
                  </a>
                  <a
                    href="#why"
                    class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                    @click="toggleMenu"
                  >
                    {{ $t('menu_why_lgn') }}
                  </a>
                  <a
                    href="#teams"
                    class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                    @click="toggleMenu"
                  >{{ $t('menu_teams') }}</a>
                  <a
                    href="#client"
                    class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                    @click="toggleMenu"
                  >{{ $t('menu_client') }}</a>
                </div>
                <div class="py-6">
                  <a
                    href="#contactus"
                    class="-mx-3 block rounded-lg px-3 py-2.5 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                    @click="toggleMenu"
                  >{{ $t('menu_contact_us') }}</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </header>

      <div class="relative isolate">
        <div
          class="mt-32 sm:mt-24 mx-auto max-w-7xl px-6 py-4 sm:py-32 lg:grid lg:grid-cols-9 lg:items-baseline lg: lg:gap-x-0 lg:px-0 lg:py-10"
        >
          <h1
            class="col-span-6 text-4xl font-bold tracking-tight text-gray-900 text-center sm:text-left sm:text-7xl mr-4"
            data-aos="fade-right"
            data-aos-easing="ease-in-sine"
          >
            Intelligent Solutions for Higher Quality
            <span class="text-[#ff6600]">Policy</span>
          </h1>
          <h1
            class="mt-6 sm:mt-0 relative col-span-3 h-full text-xl font-normal tracking-tight text-gray-900 sm:text-2xl text-center sm:text-left"
          >
            <span
              data-aos="fade-left"
              data-aos-easing="ease-in-sine"
            >{{ $t('header_description') }}</span>
          </h1>
        </div>
        <div
          class="mt-8 sm:mt-0 mx-auto max-w-7xl px-6 py-8 sm:py-32 lg:grid lg:grid-cols-9 lg:items-center lg:gap-x-0 lg:px-0 lg:py-0"
        >
          <div class="col-span-5 mx-auto lg:mx-0 lg:flex-auto hidden sm:flex">
            <img
              class="w-full h-56 object-cover"
              data-aos="fade-right"
              data-aos-duration="1000"
              data-aos-easing="ease-in-sine"
              src="https://images.unsplash.com/photo-1550592704-6c76defa9985?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            >
          </div>
          <div
            class="relative h-full col-span-4 mx-auto lg:mx-0 sm:bg-[#ff6600]"
          >
            <span
              data-aos="fade-left"
              data-aos-duration="1000"
              data-aos-easing="ease-in-sine"
            >
              <div class="grid grid-cols-3 h-full">
                <div class="col-span-3 sm:col-span-1 items-center justify-center flex flex-col text-gray-900 sm:text-white text-center px-8 py-8 sm:py-10">
                  <h3 class="text-4xl font-bold">
                    40+
                  </h3>
                  <h3 class="mt-2 leading-5 font-medium sm:font-normal">
                    {{ $t('statistics_company_clients') }}
                  </h3>
                </div>
                <div class="col-span-3 sm:col-span-1 items-center justify-center flex flex-col text-gray-900 sm:text-white text-center px-8 py-8 sm:py-10">
                  <h3 class="text-4xl font-bold">
                    7+
                  </h3>
                  <h3 class="mt-2 leading-5 font-medium sm:font-normal">
                    {{ $t('statistics_recent_portfolios_1') }} <br>{{ $t('statistics_recent_portfolios_2') }}
                  </h3>
                </div>
                <div class="col-span-3 sm:col-span-1 items-center justify-center flex flex-col text-gray-900 sm:text-white text-center px-8 py-8 sm:py-10">
                  <h3 class="text-4xl font-bold">
                    15+
                  </h3>
                  <h3 class="mt-2 leading-5 font-medium sm:font-normal">
                    {{ $t('statistics_alumni') }}
                  </h3>
                </div>
              </div>
            </span>
            <div class="absolute w-full h-auto z-0 bg-[#ff6600] inset-0 blur-2xl" style="aspect-ratio:1/1; background: rgb(255,102,0); background: radial-gradient(circle, rgba(255,102,0,0.25) 0%, rgba(255,102,0,0) 60%);" />
          </div>
        </div>
        <div
          class="mx-auto max-w-7xl px-6 py-8 sm:py-32 lg:grid lg:grid-cols-9 lg:items-center lg:gap-x-0 lg:px-0 lg:py-0"
        >
          <div
            class="w-full h-full relative col-span-3 mx-auto lg:mx-0 bg-[#ff6600] py-8 sm:py-0"
          >
            <span
              data-aos="fade-right"
              data-aos-duration="1000"
              data-aos-offset="-300"
              data-aos-easing="ease-in-sine"
            >
              <div class="h-full flex flex-col justify-center text-white text-center">
                <h3 class="flex flex-row items-center justify-center text-3xl font-medium">
                  {{ $t('header_get_started') }}<span class="ml-4"><svg
                    class="mt-1 w-16 h-16 rotate-45 border-2 border-white rounded-full p-4"
                    data-slot="icon"
                    fill="none"
                    stroke-width="3"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                    aria-hidden="true"
                  >
                    <path stroke-linecap="round" stroke-linejoin="round" d="m4.5 19.5 15-15m0 0H8.25m11.25 0v11.25" />
                  </svg></span>
                </h3>
              </div>
            </span>
          </div>
          <div
            class="col-span-6 mx-auto lg:mx-0 lg:flex-auto hidden sm:flex"
            data-aos="fade-left"
            data-aos-duration="1000"
            data-aos-easing="ease-in-sine"
          >
            <img
              class="w-full h-56 object-cover"
              src="https://images.unsplash.com/photo-1515378960530-7c0da6231fb1?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            >
          </div>
        </div>
      </div>
    </div>

    <div id="service" class="bg-white py-24">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div
          class="mx-auto lg:mx-0"
          data-aos="fade-up"
          data-aos-duration="600"
          data-aos-easing="ease-in-sine"
        >
          <p class="text-base font-semibold leading-7 text-[#ff6600]">
            {{ $t('services_title_1') }}
          </p>
          <div class="flex items-baseline">
            <h2
              class="mt-2 text-3xl w-full sm:w-2/5 font-bold tracking-tight text-gray-900 sm:text-6xl"
            >
              {{ $t('services_title') }}
            </h2>
            <p class="mt-6 w-3/5 text-lg leading-8 text-gray-500 hidden">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Beatae
              hic ullam earum doloremque quo quia quae sapiente architecto quasi
              consectetur voluptates asperiores, ex dolores eveniet possimus ab!
              Natus, ullam laudantium.
            </p>
          </div>
        </div>
        <div
          class="grid grid-cols-1 gap-x-24 gap-y-16 sm:gap-y-20 lg:grid-cols-3 lg:items-center"
        >
          <div
            class="col-span-2 mt-8 sm:mt-16 grid grid-cols-1 divide-y"
            data-aos="fade-right"
            data-aos-duration="1000"
            data-aos-easing="ease-in-sine"
          >
            <div>
              <h1
                class="py-4 sm:py-8 text-lg font-medium tracking-tight text-gray-900 sm:text-2xl"
              >
                {{ $t('services_consulting_services') }}
              </h1>
            </div>
            <div>
              <h1
                class="py-4 sm:py-8 text-lg font-medium tracking-tight text-gray-900 sm:text-2xl"
              >
                {{ $t('services_third_party_services') }}
              </h1>
            </div>
            <div>
              <h1
                class="py-4 sm:py-8 text-lg font-medium tracking-tight text-gray-900 sm:text-2xl"
              >
                {{ $t('services_advisory_services') }}
              </h1>
            </div>
          </div>
          <div class="hidden sm:block relative mt-20">
            <div class="">
              <div class="flex flex-col space-y-8">
                <div class="relative">
                  <div
                    aria-hidden="true"
                    class="hidden sm:block lg:absolute lg:inset-y-0 lg:right-0 lg:w-screen"
                    data-aos="fade-left"
                    data-aos-duration="1300"
                    data-aos-easing="ease-in-sine"
                  >
                    <svg
                      class="absolute left-1/2 -top-9 -ml-3 lg:-right-10 lg:left-auto"
                      width="108"
                      height="105"
                      fill="none"
                      viewBox="0 0 108 105"
                    >
                      <defs>
                        <pattern
                          id="02f20b47-fd69-4224-a62a-4c9de5c763f7"
                          x="0"
                          y="0"
                          width="20"
                          height="20"
                          patternUnits="userSpaceOnUse"
                        >
                          <rect
                            x="0"
                            y="0"
                            width="4"
                            height="4"
                            class="text-[#ff6600]"
                            fill="currentColor"
                          />
                        </pattern>
                      </defs>
                      <rect
                        width="404"
                        height="392"
                        fill="url(#02f20b47-fd69-4224-a62a-4c9de5c763f7)"
                      />
                    </svg>
                  </div>
                  <div
                    aria-hidden="true"
                    class="hidden sm:block lg:absolute lg:inset-y-0 lg:right-0 lg:w-screen"
                    data-aos="fade-left"
                    data-aos-duration="1000"
                    data-aos-easing="ease-in-sine"
                  >
                    <div
                      class="absolute right-1/2 -bottom-9 -ml-3 lg:right-32 lg:left-auto w-64 h-64 bg-[#ff6600]"
                    />
                  </div>
                  <div
                    class="relative mx-auto max-w-md px-6 sm:max-w-3xl lg:max-w-none lg:px-0 lg:py-0"
                    data-aos="fade-left"
                    data-aos-duration="1100"
                    data-aos-easing="ease-in-sine"
                  >
                    <div class="relative overflow-hidden pb-10 pt-64">
                      <img
                        class="absolute inset-0 h-full w-full object-cover"
                        src="https://images.unsplash.com/photo-1587089879249-87bf7d2972df?q=80&w=2952&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                        alt=""
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div id="aboutus" class="overflow-hidden bg-white py-8 sm:py-24">
      <div class="mx-auto max-w-7xl md:px-6 lg:px-0">
        <div
          class="grid grid-cols-1 gap-x-24 gap-y-16 sm:gap-y-20 lg:grid-cols-2 lg:items-center"
        >
          <div
            class="hidden sm:block relative mt-20"
            data-aos="fade-right"
            data-aos-duration="600"
            data-aos-offset="-100"
            data-aos-easing="ease-in-sine"
          >
            <div class="grid grid-cols-1 md:grid-cols-2 gap-x-8">
              <div
                class="absolute w-1/3 h-1/2 bg-[#ff6600] left-1/3 top-1/3"
              />
              <div class="flex flex-col space-y-8">
                <div class="relative">
                  <div
                    aria-hidden="true"
                    class="hidden sm:block lg:absolute lg:inset-y-0 lg:right-0 lg:w-screen"
                  >
                    <svg
                      class="absolute left-1/2 -top-9 -ml-3 lg:-right-10 lg:left-auto"
                      width="108"
                      height="105"
                      fill="none"
                      viewBox="0 0 108 105"
                    >
                      <defs>
                        <pattern
                          id="02f20b47-fd69-4224-a62a-4c9de5c763f7"
                          x="0"
                          y="0"
                          width="20"
                          height="20"
                          patternUnits="userSpaceOnUse"
                        >
                          <rect
                            x="0"
                            y="0"
                            width="4"
                            height="4"
                            class="text-[#ff6600]"
                            fill="currentColor"
                          />
                        </pattern>
                      </defs>
                      <rect
                        width="404"
                        height="392"
                        fill="url(#02f20b47-fd69-4224-a62a-4c9de5c763f7)"
                      />
                    </svg>
                  </div>
                  <div
                    class="relative mx-auto max-w-md px-6 sm:max-w-3xl lg:max-w-none lg:px-0 lg:py-0"
                  >
                    <div class="relative overflow-hidden pb-10 pt-64">
                      <img
                        class="absolute inset-0 h-full w-full object-cover"
                        src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                        alt=""
                      >
                    </div>
                  </div>
                </div>
                <div class="relative transform rotate-90">
                  <div
                    aria-hidden="true"
                    class="hidden sm:block lg:absolute lg:inset-y-0 lg:right-0 lg:w-screen"
                  >
                    <svg
                      class="absolute left-1/2 -bottom-8 -ml-3 lg:-right-10 lg:left-auto"
                      width="108"
                      height="105"
                      fill="none"
                      viewBox="0 0 108 105"
                    >
                      <defs>
                        <pattern
                          id="02f20b47-fd69-4224-a62a-4c9de5c763f7"
                          x="0"
                          y="0"
                          width="20"
                          height="20"
                          patternUnits="userSpaceOnUse"
                        >
                          <rect
                            x="0"
                            y="0"
                            width="4"
                            height="4"
                            class="text-[#ff6600]"
                            fill="currentColor"
                          />
                        </pattern>
                      </defs>
                      <rect
                        width="404"
                        height="392"
                        fill="url(#02f20b47-fd69-4224-a62a-4c9de5c763f7)"
                      />
                    </svg>
                  </div>
                  <div
                    class="relative mx-auto max-w-md px-6 sm:max-w-3xl lg:max-w-none lg:px-0 lg:py-0"
                  >
                    <div class="relative overflow-hidden pb-10 pt-64">
                      <img
                        class="absolute inset-0 h-full w-full object-cover transform -rotate-90"
                        src="https://images.unsplash.com/photo-1588600878108-578307a3cc9d?q=80&w=2952&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                        alt=""
                      >
                    </div>
                  </div>
                </div>
              </div>
              <div class="relative flex flex-col justify-center">
                <div class="">
                  <div
                    aria-hidden="true"
                    class="hidden sm:block lg:absolute lg:inset-y-0 lg:right-0 lg:w-screen"
                  >
                    <svg
                      class="absolute left-1/2 bottom-1/3 -ml-3 lg:-right-11 lg:left-auto"
                      width="108"
                      height="105"
                      fill="none"
                      viewBox="0 0 108 105"
                    >
                      <defs>
                        <pattern
                          id="02f20b47-fd69-4224-a62a-4c9de5c763f7"
                          x="0"
                          y="0"
                          width="20"
                          height="20"
                          patternUnits="userSpaceOnUse"
                        >
                          <rect
                            x="0"
                            y="0"
                            width="4"
                            height="4"
                            class="text-[#ff6600]"
                            fill="currentColor"
                          />
                        </pattern>
                      </defs>
                      <rect
                        width="404"
                        height="392"
                        fill="url(#02f20b47-fd69-4224-a62a-4c9de5c763f7)"
                      />
                    </svg>
                  </div>
                  <div
                    class="relative mx-auto max-w-md px-6 sm:max-w-3xl lg:max-w-none lg:px-0 lg:py-0"
                  >
                    <div class="relative overflow-hidden pb-10 pt-64">
                      <img
                        class="absolute inset-0 h-full w-full object-cover"
                        src="https://images.unsplash.com/photo-1474631245212-32dc3c8310c6?q=80&w=1981&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                        alt=""
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div
            class="px-6 lg:px-0 lg:pr-4 lg:pt-0"
            data-aos="fade-left"
            data-aos-duration="1000"
            data-aos-easing="ease-in-sine"
          >
            <div class="mx-auto max-w-2xl lg:mx-0 lg:max-w-lg">
              <h2 class="text-base font-semibold leading-7 text-[#ff6600]">
                {{ $t('menu_about_us') }}
              </h2>
              <p
                class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-5xl"
              >
                {{ $t('about_us_title') }}
              </p>
              <p class="mt-6 text-lg text-gray-600">
                {{ $t('about_us_description') }}
              </p>
              <ol class="mt-4 list-disc list-inside text-lg text-gray-600">
                <li>{{ $t('about_us_values_customer_centricity') }}</li>
                <li>{{ $t('about_us_values_integrity') }}</li>
                <li>{{ $t('about_us_values_synergy') }}</li>
                <li>{{ $t('about_us_values_innovation') }}</li>
              </ol>
              <div class="mt-10">
                <a
                  href="#"
                  class="text-lg font-medium leading-6 text-white bg-[#ff6600] px-6 py-4"
                >{{ $t('about_us_contact_us') }}</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div id="why" class="relative mt-32 mb-32">
      <div
        class="lg:mx-auto lg:grid lg:max-w-7xl lg:grid-cols-2 lg:items-center lg:gap-24 lg:px-8"
      >
        <div
          class="hidden sm:block relative sm:py-16 lg:py-0"
          data-aos="fade-right"
          data-aos-duration="600"
          data-aos-easing="ease-in-sine"
        >
          <div
            aria-hidden="true"
            class="hidden sm:block lg:absolute lg:inset-y-0 lg:right-0 lg:w-screen"
          >
            <div
              class="absolute inset-y-0 right-1/2 w-full bg-[#ff6600]/20 lg:right-72"
            />
            <svg
              class="absolute left-1/2 top-8 -ml-3 lg:-right-8 lg:left-auto lg:top-12"
              width="404"
              height="392"
              fill="none"
              viewBox="0 0 404 392"
            >
              <defs>
                <pattern
                  id="02f20b47-fd69-4224-a62a-4c9de5c763f7"
                  x="0"
                  y="0"
                  width="20"
                  height="20"
                  patternUnits="userSpaceOnUse"
                >
                  <rect
                    x="0"
                    y="0"
                    width="4"
                    height="4"
                    class="text-[#ff6600]"
                    fill="currentColor"
                  />
                </pattern>
              </defs>
              <rect
                width="404"
                height="392"
                fill="url(#02f20b47-fd69-4224-a62a-4c9de5c763f7)"
              />
            </svg>
          </div>
          <div
            class="relative mx-auto max-w-md px-6 sm:max-w-3xl lg:max-w-none lg:px-0 lg:py-20"
          >
            <div class="relative overflow-hidden pb-10 pt-64">
              <img
                class="absolute inset-0 h-full w-full object-cover"
                src="https://images.unsplash.com/photo-1557426272-fc759fdf7a8d?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt=""
              >
              <div class="relative px-8">
                <blockquote class="mt-8 invisible">
                  <div class="relative text-2xl text-white md:flex-grow">
                    <p class="relative">
                      Tincidunt integer commodo, cursus etiam aliquam neque, et.
                      Consectetur pretium in volutpat, diam. Montes, magna
                      cursus nulla feugiat dignissim id lobortis amet. Lorem
                      ipsum, dolor sit amet consectetur adipisicing elit.
                      Cupiditate aliquam sit adipisci odio incidunt eligendi
                      labore, beatae omnis quidem cumque ipsa sunt dolores
                      voluptas quam obcaecati laboriosam reiciendis facere
                      culpa!
                    </p>
                  </div>
                </blockquote>
              </div>
            </div>
          </div>
        </div>

        <div class="mt-16 sm:mt-0 relative mx-auto max-w-md px-6 sm:max-w-3xl lg:px-0">
          <div class="mx-auto max-w-2xl lg:mx-0 lg:max-w-lg">
            <h2
              class="text-base font-semibold leading-7 text-[#ff6600]"
              data-aos="fade-left"
              data-aos-duration="1000"
              data-aos-easing="ease-in-sine"
            >
              {{ $t('why_choose_us_title') }}
            </h2>
            <p
              class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-5xl"
              data-aos="fade-left"
              data-aos-duration="1000"
              data-aos-easing="ease-in-sine"
            >
              {{ $t('why_choose_us_subtitle') }}
            </p>
            <dl class="mt-5 grid grid-cols-1 gap-2">
              <div
                class="py-2"
                data-aos="fade-left"
                data-aos-duration="1000"
                data-aos-delay="50"
                data-aos-easing="ease-in-sine"
              >
                <dd
                  class="mt-1 text-3xl font-semibold tracking-tight text-[#ff6600]"
                >
                  01
                </dd>
                <dt class="text-lg font-normal text-gray-900">
                  {{ $t('why_choose_us_point_1_description') }}
                </dt>
              </div>
              <div
                class="py-2"
                data-aos="fade-left"
                data-aos-duration="1000"
                data-aos-delay="150"
                data-aos-easing="ease-in-sine"
              >
                <dd
                  class="mt-1 text-3xl font-semibold tracking-tight text-[#ff6600]"
                >
                  02
                </dd>
                <dt class="text-lg font-normal text-gray-900">
                  {{ $t('why_choose_us_point_2_description') }}
                </dt>
              </div>
              <div
                class="py-2"
                data-aos="fade-left"
                data-aos-duration="1000"
                data-aos-delay="250"
                data-aos-easing="ease-in-sine"
              >
                <dd
                  class="mt-1 text-3xl font-semibold tracking-tight text-[#ff6600]"
                >
                  03
                </dd>
                <dt class="text-lg font-normal text-gray-900">
                  {{ $t('why_choose_us_point_3_description') }}
                </dt>
              </div>
            </dl>
          </div>
        </div>
      </div>
    </div>

    <div id="project" class="bg-white py-8 sm:py-24">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div
          class="mx-auto lg:mx-0"
          data-aos="fade-up"
          data-aos-duration="600"
          data-aos-offset="-100"
          data-aos-easing="ease-in-sine"
        >
          <p class="text-base font-semibold leading-7 text-[#ff6600]">
            {{ $t('projects_title_1') }}
          </p>
          <div class="flex flex-col sm:flex-row items-baseline sm:space-x-8">
            <h2
              class="mt-2 text-3xl sm:w-2/5 font-bold tracking-tight text-gray-900 sm:text-6xl"
            >
              {{ $t('projects_title') }}
            </h2>
            <p class="mt-6 sm:pl-20 sm:w-3/5 text-lg leading-8 text-gray-500 hidden">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Beatae
              hic ullam earum doloremque quo quia quae sapiente architecto quasi
              consectetur voluptates asperiores, ex dolores eveniet possimus ab!
            </p>
          </div>
        </div>
        <dl class="mt-16 grid max-w-xl grid-cols-1 gap-x-8 gap-y-16 lg:max-w-none lg:grid-cols-3">
          <div
            class="flex flex-col"
            data-aos="fade-up"
            data-aos-duration="1000"
            data-aos-delay="200"
            data-aos-easing="ease-in-sine"
          >
            <dt class="text-lg font-bold leading-7 text-gray-900">
              <div class="mb-2 flex h-24 w-24 items-center justify-center rounded-lg">
                <img src="BKPM.png" class="">
              </div>
              Rencana Aksi Nasional Hilirisasi Investasi Strategi Tahun Anggaran 2023
            </dt>
            <dd class="mt-1 flex flex-auto flex-col text-base leading-7 text-gray-500">
              <p class="flex-auto">
                {{ $t('projects_project_1_description') }}
              </p>
            </dd>
          </div>
          <div
            class="flex flex-col"
            data-aos="fade-up"
            data-aos-duration="1000"
            data-aos-delay="400"
            data-aos-easing="ease-in-sine"
          >
            <dt class="text-lg font-bold leading-7 text-gray-900">
              <div class="mb-2 flex h-24 w-24 items-center justify-center rounded-lg">
                <img src="BKPM.png" class="">
              </div>
              Kajian Kebijakan Penanaman Modal mengenai Dampak Survey Kemudahan Berusaha terhadap Arus Foreign Direct Investment di Negara-Negara Berkembang
            </dt>
            <dd class="mt-1 flex flex-auto flex-col text-base leading-7 text-gray-500">
              <p class="flex-auto">
                {{ $t('projects_project_2_description') }}
              </p>
            </dd>
          </div>
          <div
            class="flex flex-col"
            data-aos="fade-up"
            data-aos-duration="1000"
            data-aos-delay="600"
            data-aos-easing="ease-in-sine"
          >
            <dt class="text-lg font-bold leading-7 text-gray-900">
              <div class="mb-2 flex h-24 w-24 p-4 items-center justify-center rounded-lg">
                <img src="kpo.png" class="">
              </div>
              Kajian Menuju Muda-mudi Indonesia Sehat Mental
            </dt>
            <dd class="mt-1 flex flex-auto flex-col text-base leading-7 text-gray-500">
              <p class="flex-auto">
                {{ $t('projects_project_3_description') }}
              </p>
            </dd>
          </div>
        </dl>
      </div>
    </div>

    <div id="teams" class="bg-gray-900 py-24 sm:py-32">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div
          class=""
          data-aos="fade-up"
          data-aos-duration="600"
          data-aos-easing="ease-in-sine"
        >
          <h2 class="text-base font-semibold leading-7 text-[#ff6600]">
            {{ $t('our_team_title') }}
          </h2>
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
            {{ $t('our_team_subtitle') }}
          </h2>
          <p class="mt-4 text-lg leading-8 text-gray-400">
            {{ $t('our_team_description') }}
          </p>
        </div>
        <ul
          role="list"
          class="mx-auto mt-2 grid max-w-2xl grid-cols-1 gap-6 sm:grid-cols-3 lg:mx-0 lg:max-w-none lg:gap-8"
        >
          <li
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-delay="200"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-4 pt-12"
          >
            <img class="bg-gray-300 w-full h-auto aspect-[1/1] flex-none object-cover" src="https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/team/Ansy%20Alghasi_ga26aHAjq.png?updatedAt=1718317891730" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-xl font-semibold leading-10 tracking-tight text-white">
                Ansy Alghasi
              </h3>
              <p class="text-lg leading-6 text-gray-50">
                Managing Director
              </p>
              <p class="mt-2 text-lg leading-6 text-gray-400">
                New South Wales University
              </p>
              <ul role="list" class="mt-6 flex items-center gap-x-6">
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-6 w-6"
                      fill="currentColor"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">X</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z" />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">LinkedIn</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path fill-rule="evenodd" d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z" clip-rule="evenodd" />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-delay="400"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-4 pt-12"
          >
            <img class="bg-gray-300 w-full h-auto aspect-[1/1] flex-none object-cover" src="https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/team/Megawanti_s_W36pCIEq1O.png?updatedAt=1718317891174" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-xl font-semibold leading-10 tracking-tight text-white">
                Megawanti
              </h3>
              <p class="text-lg leading-6 text-gray-50">
                Policy & Research Director
              </p>
              <p class="mt-2 text-lg leading-6 text-gray-400">
                Wageningen University
              </p>
              <ul role="list" class="mt-6 flex items-center gap-x-6">
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-6 w-6"
                      fill="currentColor"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">X</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z" />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">LinkedIn</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path fill-rule="evenodd" d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z" clip-rule="evenodd" />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-delay="600"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-4 pt-12"
          >
            <img class="bg-gray-300 w-full h-auto aspect-[1/1] flex-none object-cover" src="https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/team/Fitri%20N.%20Anggraeni_square_q0sjPT-3l.png?updatedAt=1718317889800" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-xl font-semibold leading-10 tracking-tight text-white">
                ⁠Fitri N. Anggraeni
              </h3>
              <p class="text-lg leading-6 text-gray-50">
                Marketing & Communication Director
              </p>
              <p class="mt-2 text-lg leading-6 text-gray-400">
                Institut Teknologi Bandung
              </p>
              <ul role="list" class="mt-6 flex items-center gap-x-6">
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-6 w-6"
                      fill="currentColor"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">X</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z" />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">LinkedIn</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path fill-rule="evenodd" d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z" clip-rule="evenodd" />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
        </ul>
      </div>
    </div>

    <div class="bg-gray-900 pb-40">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div
          class=""
          data-aos="fade-up"
          data-aos-duration="600"
          data-aos-easing="ease-in-sine"
        >
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
            {{ $t('our_commissioner_title') }}
          </h2>
        </div>
        <ul
          role="list"
          class="mx-auto mt-2 grid max-w-2xl grid-cols-1 gap-6 sm:grid-cols-2 lg:mx-0 lg:max-w-none lg:grid-cols-3 lg:gap-8"
        >
          <li
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-delay="200"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-4 pt-12"
          >
            <img class="bg-gray-300 w-full h-auto aspect-[1/1] flex-none object-cover" src="https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/team/Yosua%20Yosafat%20Andre_k8HiFC0Pa.png?updatedAt=1718317891862" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-xl font-semibold leading-10 tracking-tight text-white">
                Yosua Yosafat Andre
              </h3>
              <p class="text-lg leading-6 text-gray-50">
                Commissioner
              </p>
              <p class="mt-2 text-lg leading-6 text-gray-400">
                Monash University
              </p>
              <ul role="list" class="mt-6 flex items-center gap-x-6">
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-6 w-6"
                      fill="currentColor"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">X</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z" />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">LinkedIn</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path fill-rule="evenodd" d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z" clip-rule="evenodd" />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-delay="400"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-4 pt-12"
          >
            <img class="bg-gray-300 w-full h-auto aspect-[1/1] flex-none object-cover" src="https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/team/M.%20Diaz%20Alichsan_0jlVxc8yx.png?updatedAt=1718317890669" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-xl font-semibold leading-10 tracking-tight text-white">
                M. Diaz Alichsan
              </h3>
              <p class="text-lg leading-6 text-gray-50">
                Independent Commissioner
              </p>
              <p class="mt-2 text-lg leading-6 text-gray-400">
                Erasmus University Rotterdam
              </p>
              <ul role="list" class="mt-6 flex items-center gap-x-6">
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-6 w-6"
                      fill="currentColor"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">X</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z" />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">LinkedIn</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path fill-rule="evenodd" d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z" clip-rule="evenodd" />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-delay="600"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-4 pt-12"
          >
            <img class="bg-gray-300 w-full h-auto aspect-[1/1] flex-none object-cover" src="https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/team/Asep%20Cahyana_YA3FnSR7D.png?updatedAt=1718317891100" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-xl font-semibold leading-10 tracking-tight text-white">
                Asep Cahyana
              </h3>
              <p class="text-lg leading-6 text-gray-50">
                Commissioner
              </p>
              <p class="mt-2 text-lg leading-6 text-gray-400">
                Universitas Gajah Mada
              </p>
              <ul role="list" class="mt-6 flex items-center gap-x-6">
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-6 w-6"
                      fill="currentColor"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">X</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z" />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">LinkedIn</span>
                    <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                      <path fill-rule="evenodd" d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z" clip-rule="evenodd" />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
        </ul>
      </div>
    </div>

    <div id="client" class="bg-white pt-24">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div
          data-aos="fade-left"
          data-aos-duration="600"
          data-aos-easing="ease-in-sine"
          class="mx-auto max-w-2xl lg:max-w-none"
        >
          <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">
            {{ $t('trusted_by') }}
          </h2>
        </div>
        <div
          data-aos="fade-left"
          data-aos-duration="1000"
          data-aos-delay="200"
          data-aos-easing="ease-in-sine"
          class="mt-4"
        >
          <div class="relative overflow-hidden whitespace-nowrap">
            <div class="inline-block animate-slide" :style="{ width: `${totalWidth}px` }">
              <img v-for="(image, index) in extendedImages" :key="`image1-${index}`" :src="image" class="inline-block w-40 h-auto object-scale-down mx-4">
            </div>
            <div class="inline-block animate-slide" :style="{ width: `${totalWidth}px` }">
              <img v-for="(image, index) in extendedImages" :key="`image2-${index}`" :src="image" class="inline-block w-40 h-auto object-scale-down mx-4">
            </div>
          </div>
        </div>
      </div>
    </div>

    <div id="contactus" class="relative isolate bg-white">
      <div class="mx-auto grid max-w-7xl grid-cols-1 lg:grid-cols-2">
        <div
          class="relative px-6 pb-20 pt-24 sm:pt-32 lg:static lg:px-8 lg:py-48"
          data-aos="fade-right"
          data-aos-duration="600"
          data-aos-easing="ease-in-sine"
        >
          <div class="mx-auto max-w-xl lg:mx-0 lg:max-w-lg">
            <div
              class="absolute inset-y-0 left-0 -z-10 w-full overflow-hidden lg:w-1/2"
            />

            <h2 class="text-base font-semibold leading-7 text-[#ff6600]">
              {{ $t('lets_talk') }}
            </h2>
            <h2 class="text-3xl font-bold tracking-tight text-gray-900">
              {{ $t('get_in_touch') }}
            </h2>
            <dl class="mt-10 space-y-4 text-base leading-7 text-gray-600">
              <div class="flex gap-x-4">
                <dt class="flex-none">
                  <span class="sr-only">{{ $t('address') }}</span>
                  <svg
                    class="h-7 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke-width="1.5"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008z"
                    />
                  </svg>
                </dt>
                <dd>
                  Apartemen Vittoria Residence, Jl. Raya DaanMogot No.KM 13,
                  RT.10/RW.2, Rw. Buaya, Kecamatan Cengkareng, Kota Jakarta
                  Barat, Daerah KhususIbukota Jakarta 11740
                </dd>
              </div>
              <div class="flex gap-x-4">
                <dt class="flex-none">
                  <span class="sr-only">{{ $t('form_phone_number') }}</span>
                  <svg
                    class="h-7 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke-width="1.5"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"
                    />
                  </svg>
                </dt>
                <dd>
                  <a
                    class="hover:text-gray-900"
                    href="https://api.whatsapp.com/send?phone=6281314626624&text=Halo Lensa Garuda Nusantara"
                    target="_blank"
                  >+6281 314 626 624 (Ansy)</a>
                </dd>
              </div>
              <div class="flex gap-x-4">
                <dt class="flex-none">
                  <span class="sr-only">Email</span>
                  <svg
                    class="h-7 w-6 text-gray-400"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke-width="1.5"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"
                    />
                  </svg>
                </dt>
                <dd>
                  <a
                    class="hover:text-gray-900"
                    href="mailto:lensa.garuda@gmail.com"
                  >lensa.garuda@gmail.com</a>
                </dd>
              </div>
            </dl>
          </div>
        </div>
        <form
          class="px-6 pb-24 pt-20 sm:pb-32 lg:px-8 lg:py-48"
          data-aos="fade-left"
          data-aos-duration="800"
          data-aos-delay="200"
          data-aos-easing="ease-in-sine"
          @submit.prevent="sendMessage"
        >
          <div class="mx-auto max-w-xl lg:mr-0 lg:max-w-lg">
            <div class="grid grid-cols-1 gap-x-8 gap-y-6 sm:grid-cols-2">
              <div class="sm:col-span-2">
                <label
                  for="name"
                  class="block text-sm font-semibold leading-6 text-gray-900"
                >Name</label>
                <div class="mt-2.5">
                  <input
                    id="name"
                    v-model="name"
                    type="text"
                    autocomplete="name"
                    required
                    class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                  >
                </div>
              </div>
              <div class="sm:col-span-2">
                <label
                  for="message"
                  class="block text-sm font-semibold leading-6 text-gray-900"
                >Message</label>
                <div class="mt-2.5">
                  <textarea
                    id="message"
                    v-model="message"
                    name="message"
                    rows="4"
                    required
                    class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                  />
                </div>
              </div>
            </div>
            <div class="mt-8 flex justify-end">
              <button
                type="submit"
                class="w-full sm:w-max rounded-md bg-[#ff6600] px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-sm hover:bg-orange-600 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
              >
                Send message
              </button>
            </div>
          </div>
        </form>
      </div>
    </div>

    <footer
      class="bg-gray-900"
      aria-labelledby="footer-heading"
      data-aos="fade-up"
      data-aos-duration="800"
      data-aos-easing="ease-out-cubic"
    >
      <h2 id="footer-heading" class="sr-only">
        Footer
      </h2>
      <div class="mx-auto max-w-7xl px-6 pb-8 pt-16 lg:px-8">
        <p class="text-center mx-auto text-4xl text-white">
          Please feel free to get in touch with us
        </p>
        <div class="pt-8 lg:flex lg:items-center lg:justify-between">
          <dl
            class="mt-10 grid grid-cols-1 md:grid-cols-3 gap-x-16 text-base leading-7 text-gray-300 mx-auto"
          >
            <div class="flex gap-x-4">
              <dt class="flex-none">
                <span class="sr-only">Address</span>
                <svg
                  class="h-7 w-6 text-gray-400"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008z"
                  />
                </svg>
              </dt>
              <dd>
                Apartemen Vittoria Residence, Jl. Raya DaanMogot No.KM 13,
                RT.10/RW.2, Rw. Buaya, Kecamatan Cengkareng, Kota Jakarta Barat,
                Daerah KhususIbukota Jakarta 11740
              </dd>
            </div>
            <div class="flex gap-x-4 text-gray-300">
              <dt class="flex-none">
                <span class="sr-only">Telephone</span>
                <svg
                  class="h-7 w-6 text-gray-400"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"
                  />
                </svg>
              </dt>
              <dd>
                <a
                  class="hover:text-[#ff6600]"
                  href="https://api.whatsapp.com/send?phone=6281314626624&text=Halo Lensa Garuda Nusantara"
                  target="_blank"
                >+6281 314 626 624 (Ansy)</a>
              </dd>
            </div>
            <div class="flex gap-x-4 text-gray-300">
              <dt class="flex-none">
                <span class="sr-only">Email</span>
                <svg
                  class="h-7 w-6 text-gray-400"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"
                  />
                </svg>
              </dt>
              <dd>
                <a
                  class="hover:text-[#ff6600]"
                  href="mailto:lensa.garuda@gmail.com"
                >lensa.garuda@gmail.com</a>
              </dd>
            </div>
          </dl>
        </div>

        <div
          class="mt-8 border-t border-gray-100/10 pt-8 md:flex md:items-center md:justify-between"
        >
          <div class="flex space-x-6 md:order-2">
            <a href="#" class="text-gray-400 hover:text-gray-500">
              <span class="sr-only">Facebook</span>
              <svg
                class="h-6 w-6"
                fill="currentColor"
                viewBox="0 0 24 24"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
            <a href="#" class="text-gray-400 hover:text-gray-500">
              <span class="sr-only">Instagram</span>
              <svg
                class="h-6 w-6"
                fill="currentColor"
                viewBox="0 0 24 24"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
            <a href="#" class="text-gray-400 hover:text-gray-500">
              <span class="sr-only">X</span>
              <svg
                class="h-6 w-6"
                fill="currentColor"
                viewBox="0 0 24 24"
                aria-hidden="true"
              >
                <path
                  d="M13.6823 10.6218L20.2391 3H18.6854L12.9921 9.61788L8.44486 3H3.2002L10.0765 13.0074L3.2002 21H4.75404L10.7663 14.0113L15.5685 21H20.8131L13.6819 10.6218H13.6823ZM11.5541 13.0956L10.8574 12.0991L5.31391 4.16971H7.70053L12.1742 10.5689L12.8709 11.5655L18.6861 19.8835H16.2995L11.5541 13.096V13.0956Z"
                />
              </svg>
            </a>
            <a href="#" class="text-gray-400 hover:text-gray-500">
              <span class="sr-only">GitHub</span>
              <svg
                class="h-6 w-6"
                fill="currentColor"
                viewBox="0 0 24 24"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
            <a href="#" class="text-gray-400 hover:text-gray-500">
              <span class="sr-only">YouTube</span>
              <svg
                class="h-6 w-6"
                fill="currentColor"
                viewBox="0 0 24 24"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M19.812 5.418c.861.23 1.538.907 1.768 1.768C21.998 8.746 22 12 22 12s0 3.255-.418 4.814a2.504 2.504 0 0 1-1.768 1.768c-1.56.419-7.814.419-7.814.419s-6.255 0-7.814-.419a2.505 2.505 0 0 1-1.768-1.768C2 15.255 2 12 2 12s0-3.255.417-4.814a2.507 2.507 0 0 1 1.768-1.768C5.744 5 11.998 5 11.998 5s6.255 0 7.814.418ZM15.194 12 10 15V9l5.194 3Z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
          </div>
          <p class="mt-8 text-xs leading-5 text-gray-500 md:order-1 md:mt-0">
            &copy; 2024 LensaGarudaNusantara - All Right Reserved
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import AOS from 'aos'

export default {
  data () {
    return {
      images: [
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/The_Global_Fund_logo_khXQoYG3y.png?updatedAt=1718604689814',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/pemberdayaan-perempuan-perlindungan-anak-logo-40161DD34C-seeklogo.com_k8F32Nf4T.png?updatedAt=1718604688924',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/images%20(1)_yaE7crSka.png?updatedAt=1718604688378',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/1_QEps725rQjfgqNnlbRYb1g_wiF8CiFDq.png?updatedAt=1718604688316',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/Logo-Julius-Center_sf5jPRKt5.jpg?updatedAt=1718604688301',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/images%20(2)_myHoETpPD.png?updatedAt=1718604687370',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/Logo-Tengah-Stack-Up-1-510x510_n61KTgPLr.jpg?updatedAt=1718604687385',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/images%20(3)_CY7cZVpZC.png?updatedAt=1718604686599',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/brawijayaclinic-logo_GJeRp7cdH.jpg?updatedAt=1718604686178',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/images%20(1)_amNlPrJ2k.jpeg?updatedAt=1718604685707',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/images_mqAN6vBM5.jpeg?updatedAt=1718604685669',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/images%20(2)_lK93KTDdw.jpeg?updatedAt=1718604685334',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/logo-RSCM_YA-MiRLYt.png?updatedAt=1718604684925',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/kementrian%20bappenas_8kruqNpNC.png?updatedAt=1718604683915',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/transport%20for%20london_yz77mR0Pg.png?updatedAt=1718604683886',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/kementrian%20perindustrian_WT8dCIhMJ.png?updatedAt=1718604683817',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/kementrian%20pekerjaan%20umum%20dan%20perumahan%20rakyat_s3-KVlvrp.png?updatedAt=1718604683775',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/kominfo_NS6M2c1cO.jpg?updatedAt=1718604683341',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/kementrian%20pendayagunaan%20aparatur%20negara_M3DVM2Hb7.png?updatedAt=1718604683071',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/mind%20id_Hkb9O-f61.jpg?updatedAt=1718604682625',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/pemerintah%20kabupaten%20badung_PnZnjv7Oe.png?updatedAt=1718604682626',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/iigf_L5x606dSz.jpg?updatedAt=1718604682426',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/Logo_of_the_Ministry_of_Health_of_the_Republic_of_Indonesia_Z32rMI7bP.png?updatedAt=1718604681861',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/(Bukit_Asam)_Logo_CMYK-01_JzoIc22mz.png?updatedAt=1718604680413',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/AIC-logo_hQzgL9Z49.jpg?updatedAt=1718604680345',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/5de0e25144da7_20191129161809-1_5LTlWcfjj.png?updatedAt=1718604680345',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/logo-pln-ok_Gp9olJjM8.jpg?updatedAt=1718604680300',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/FREEPORT_cP6ouH7dF.jpg?updatedAt=1718604679564',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/Logo-Inalum-Operating-1_CvE8VsV95.png?updatedAt=1718604679042',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/Ristek-BRIN1_bU8FonwXw.jpg?updatedAt=1718604678978',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/images__UvI9khCw.png?updatedAt=1718604678755',
        'https://ik.imagekit.io/9ceqtmg8a7b/client/lgn/our%20client/Download-Logo-PT-Timah-PNG_7o1LMXLq1.png?updatedAt=1718604678318'
      ],
      name: '',
      message: '',
      isMenuOpen: false,
      showLanguageSwitch: false
    }
  },
  head () {
    return {
      link: [
        {
          rel: 'stylesheet',
          href: 'https://unpkg.com/aos@2.3.1/dist/aos.css'
        },
        {
          rel: 'stylesheet',
          href: 'https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css'
        }
      ],
      script: [
        {
          src: 'https://unpkg.com/aos@2.3.1/dist/aos.js',
          body: true,
          async: true,
          defer: true
        },
        {
          src: 'https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js',
          body: true,
          async: true,
          defer: true
        }
      ]
    }
  },
  computed: {
    extendedImages () {
      return [...this.images, ...this.images]
    },
    totalWidth () {
      return this.extendedImages.length * 160
    }
  },
  mounted () {
    AOS.init({
    })
  },
  methods: {
    sendMessage () {
      const phoneNumber = '6281314626624'
      const text = `hello! my name ${this.name}%0A, ${this.message}`
      const whatsappUrl = `https://wa.me/${phoneNumber}?text=${text}`
      window.open(whatsappUrl, '_blank')
    },
    toggleMenu () {
      this.isMenuOpen = !this.isMenuOpen
    },
    switchLanguage (code = 'en') {
      this.$i18n.setLocale(code)
      // const oldCode = this.$i18n.locale
      // this.showLanguageSwitch = false
      // if (code === this.$i18n.locale) {
      //   return
      // }

      // this.$i18n.locale = code
      // window.history.replaceState('', '', this.switchLocalePath(code))
      // this.$nuxt.$emit('languageChanged', { code, oldCode })
    },
    getLangImage (code) {
      return require(`~/assets/images/${code}.svg`)
    },
    getLangShortName (code) {
      switch (code) {
        case 'id':
          return 'ID'
        case 'en':
          return 'EN'
      }
    }
  }
}
</script>
<style>
.bg-nav {
  -webkit-backdrop-filter: blur(12px);
  backdrop-filter: blur(12px);
  background-color: rgba(255, 255, 255, 0.65);
  }
@keyframes slide {
  0% {
    transform: translateX(0%);
  }
  100% {
    transform: translateX(-100%);
  }
}
.animate-slide {
  display: inline-flex;
  animation: slide 120s linear infinite;
}
</style>
