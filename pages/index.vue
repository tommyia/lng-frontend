<!-- Please remove this file from your project -->
<template>
  <div>
    <div class="bg-white">
      <header class="absolute inset-x-0 top-0 z-50">
        <nav
          class="relative mx-auto max-w-7xl px-6 lg:px-0 flex items-center justify-between p-6"
          aria-label="Global"
          data-aos="fade-down"
          data-aos-duration="400"
          data-aos-offset="0"
          data-aos-easing="ease-in-sine"
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
            >About Us</a>
            <a
              href="#service"
              class="text-sm font-semibold leading-6 text-gray-900"
            >Service</a>
            <a
              href="#why"
              class="text-sm font-semibold leading-6 text-gray-900"
            >Why LGN?</a>
            <a
              href="#teams"
              class="text-sm font-semibold leading-6 text-gray-900"
            >Teams</a>
            <a
              href="#client"
              class="text-sm font-semibold leading-6 text-gray-900"
            >Client</a>
          </div>
          <div class="hidden lg:flex lg:flex-1 lg:justify-end">
            <a
              href="#"
              class="text-sm font-semibold leading-6 text-white bg-[#ff6600] px-4 py-2"
            >Let's Talk <span aria-hidden="true">&rarr;</span></a>
          </div>
          <div class="absolute bottom-0 w-full h-0.5 bg-[#ff6600] sm:hidden" style="background: linear-gradient(90deg, rgba(255, 102, 0, 0) 0%, rgba(255, 102, 0, 0.52) 51.5%, rgba(255, 102, 0, 0) 100%); opacity: 1;" />
        </nav>
        <!-- Mobile menu, show/hide based on menu open state. -->
        <div class="hidden" role="dialog" aria-modal="true">
          <!-- Background backdrop, show/hide based on slide-over state. -->
          <div class="fixed inset-0 z-50" />
          <div
            class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10"
          >
            <div class="flex items-center justify-between">
              <a href="#" class="-m-1.5 p-1.5">
                <span class="sr-only">Your Company</span>
                <img
                  class="h-8 w-auto"
                  src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=600"
                  alt=""
                >
              </a>
              <button
                type="button"
                class="-m-2.5 rounded-md p-2.5 text-gray-700"
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
                    href="#"
                    class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                  >Product</a>
                  <a
                    href="#"
                    class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                  >Features</a>
                  <a
                    href="#"
                    class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                  >Marketplace</a>
                  <a
                    href="#"
                    class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                  >Company</a>
                </div>
                <div class="py-6">
                  <a
                    href="#"
                    class="-mx-3 block rounded-lg px-3 py-2.5 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                  >Log in</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </header>

      <div class="relative isolate">
        <div
          class="mt-32 sm:mt-24 mx-auto max-w-7xl px-6 py-4 sm:py-32 lg:grid lg:grid-cols-9 lg:items-center lg:gap-x-0 lg:px-0 lg:py-10"
        >
          <div class="col-span-6 mx-auto lg:mx-0 lg:flex-auto">
            <h1
              class="text-4xl font-bold tracking-tight text-gray-900 text-center sm:text-left sm:text-7xl mr-4"
              data-aos="fade-right"
              data-aos-easing="ease-in-sine"
            >
              Intelligent Solution for Higher Quality
              <span class="text-[#ff6600]">Policy</span>
            </h1>
          </div>
          <div class="mt-6 sm:mt-0 relative col-span-3 mx-auto lg:mx-0">
            <h1
              class="text-xl font-normal tracking-tight text-gray-900 sm:text-3xl text-center sm:text-left absolute inset-0"
              data-aos="fade-left"
              data-aos-easing="ease-in-sine"
            >
              A tailor-made service. We have the people you need.
            </h1>
          </div>
        </div>
        <div
          class="mt-8 sm:mt-0 mx-auto max-w-7xl px-6 py-8 sm:py-32 lg:grid lg:grid-cols-9 lg:items-center lg:gap-x-0 lg:px-0 lg:py-0"
        >
          <div class="col-span-6 mx-auto lg:mx-0 lg:flex-auto hidden sm:flex">
            <img
              class="w-full h-56 object-cover"
              data-aos="fade-right"
              data-aos-offset="300"
              data-aos-duration="1000"
              data-aos-easing="ease-in-sine"
              src="https://images.unsplash.com/photo-1550592704-6c76defa9985?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            >
          </div>
          <div
            class="relative h-full col-span-3 mx-auto lg:mx-0 sm:bg-[#ff6600]"
            data-aos="fade-left"
            data-aos-offset="300"
            data-aos-duration="1000"
            data-aos-easing="ease-in-sine"
          >
            <div class="grid grid-cols-2 h-full">
              <div class="col-span-2 sm:col-span-1 items-center justify-center flex flex-col text-gray-900 sm:text-white text-center px-8 py-8 sm:py-10">
                <h3 class="text-4xl font-bold">
                  40+
                </h3>
                <h3 class="mt-2 leading-5 font-medium sm:font-normal">
                  Company Clients of Fellows LGN
                </h3>
              </div>
              <div class="col-span-2 sm:col-span-1 items-center justify-center flex flex-col text-gray-900 sm:text-white text-center px-8 py-8 sm:py-10">
                <h3 class="text-4xl font-bold">
                  7+
                </h3>
                <h3 class="mt-2 leading-5 font-medium sm:font-normal">
                  Recent <br>Portfolios
                </h3>
              </div>
            </div>
            <div class="absolute w-full h-auto z-0 bg-[#ff6600] inset-0 blur-2xl" style="aspect-ratio:1/1; background: rgb(255,102,0); background: radial-gradient(circle, rgba(255,102,0,0.25) 0%, rgba(255,102,0,0) 60%);" />
          </div>
        </div>
        <div
          class="mx-auto max-w-7xl px-6 py-8 sm:py-32 lg:grid lg:grid-cols-9 lg:items-center lg:gap-x-0 lg:px-0 lg:py-0"
        >
          <div
            class="w-full h-full relative col-span-3 mx-auto lg:mx-0 bg-[#ff6600] py-8 sm:py-0"
            data-aos="fade-right"
            data-aos-duration="1000"
            data-aos-easing="ease-in-sine"
          >
            <div class="h-full flex flex-col justify-center text-white text-center">
              <h3 class="flex flex-row items-center justify-center text-3xl font-medium">
                Get Started<span class="ml-4"><svg
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
          data-aos-duration="1000"
          data-aos-offset="50"
          data-aos-easing="ease-in-sine"
        >
          <p class="text-base font-semibold leading-7 text-[#ff6600]">
            Our Service
          </p>
          <div class="flex items-baseline">
            <h2
              class="mt-2 text-3xl w-full sm:w-2/5 font-bold tracking-tight text-gray-900 sm:text-6xl"
            >
              What Services We're Offering
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
            data-aos-offset="100"
            data-aos-easing="ease-in-sine"
          >
            <div>
              <h1
                class="py-4 sm:py-8 text-lg font-medium tracking-tight text-gray-900 sm:text-2xl"
              >
                Consulting Services in Public Policy
              </h1>
            </div>
            <div>
              <h1
                class="py-4 sm:py-8 text-lg font-medium tracking-tight text-gray-900 sm:text-2xl"
              >
                3rd Party Researchers, Surveyors, and Data Providers
              </h1>
            </div>
            <div>
              <h1
                class="py-4 sm:py-8 text-lg font-medium tracking-tight text-gray-900 sm:text-2xl"
              >
                Advisory Services from Experts and Thought Leaders
              </h1>
            </div>
          </div>
          <div class="relative mt-20">
            <div class="">
              <div class="flex flex-col space-y-8">
                <div class="relative">
                  <div
                    aria-hidden="true"
                    class="hidden sm:block lg:absolute lg:inset-y-0 lg:right-0 lg:w-screen"
                    data-aos="fade-left"
                    data-aos-duration="1300"
                    data-aos-offset="100"
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
                    data-aos-offset="100"
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
                    data-aos-offset="100"
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

    <div id="aboutus" class="overflow-hidden bg-white py-24 sm:py-32">
      <div class="mx-auto max-w-7xl md:px-6 lg:px-0">
        <div
          class="grid grid-cols-1 gap-x-24 gap-y-16 sm:gap-y-20 lg:grid-cols-2 lg:items-center"
        >
          <div
            class="relative mt-20"
            data-aos="fade-right"
            data-aos-duration="1000"
            data-aos-offset="50"
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
            data-aos-offset="50"
            data-aos-easing="ease-in-sine"
          >
            <div class="mx-auto max-w-2xl lg:mx-0 lg:max-w-lg">
              <h2 class="text-base font-semibold leading-7 text-[#ff6600]">
                About Us
              </h2>
              <p
                class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-5xl"
              >
                Deliver a higher quality of policies & peace of mind
              </p>
              <p class="mt-6 text-lg text-gray-600">
                Integrity, synergy, innovation and happiness are our core values
                in running Lensa Garuda Nusantara (LGN). It is our identities in
                delivering our best service with nation’s pride and
                international standards.
              </p>
              <div class="mt-8">
                <a
                  href="#"
                  class="text-lg font-medium leading-6 text-white bg-[#ff6600] px-6 py-4"
                >Get Started</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div id="why" class="relative mt-32 mb-32">
      <div
        class="lg:mx-auto lg:grid lg:max-w-7xl lg:grid-cols-2 lg:items-start lg:gap-24 lg:px-8"
      >
        <div
          class="relative sm:py-16 lg:py-0"
          data-aos="fade-right"
          data-aos-duration="1000"
          data-aos-offset="0"
          data-aos-delay="200"
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
              data-aos-offset="0"
              data-aos-easing="ease-in-sine"
            >
              Why Choose Us
            </h2>
            <p
              class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-5xl"
              data-aos="fade-left"
              data-aos-duration="1000"
              data-aos-offset="0"
              data-aos-easing="ease-in-sine"
            >
              Why You Should Choose LensaGaruda
            </p>
            <dl class="mt-5 grid grid-cols-1 gap-2">
              <div
                class="py-2"
                data-aos="fade-left"
                data-aos-duration="1000"
                data-aos-offset="100"
                data-aos-delay="100"
                data-aos-easing="ease-in-sine"
              >
                <dd
                  class="mt-1 text-3xl font-semibold tracking-tight text-[#ff6600]"
                >
                  01
                </dd>
                <dt class="text-lg font-normal text-gray-900">
                  LGN's greatest asset is its researchers who are graduates or
                  students from various leading universities in Indonesia and
                  the world
                </dt>
              </div>
              <div
                class="py-2"
                data-aos="fade-left"
                data-aos-duration="1000"
                data-aos-offset="100"
                data-aos-delay="200"
                data-aos-easing="ease-in-sine"
              >
                <dd
                  class="mt-1 text-3xl font-semibold tracking-tight text-[#ff6600]"
                >
                  02
                </dd>
                <dt class="text-lg font-normal text-gray-900">
                  LGN has diverse backgrounds ranging from the corporate world
                  to bureaucrats so that they can compile studies that involve
                  various perspectives.
                </dt>
              </div>
              <div
                class="py-2"
                data-aos="fade-left"
                data-aos-duration="1000"
                data-aos-offset="100"
                data-aos-delay="300"
                data-aos-easing="ease-in-sine"
              >
                <dd
                  class="mt-1 text-3xl font-semibold tracking-tight text-[#ff6600]"
                >
                  03
                </dd>
                <dt class="text-lg font-normal text-gray-900">
                  LGN's research is not only academic in nature but is oriented
                  towards practical policy recommendations that are more useful
                  for the government in carry out policy execution
                </dt>
              </div>
              <div
                class="py-2"
                data-aos="fade-left"
                data-aos-duration="1000"
                data-aos-offset="-20"
                data-aos-delay="400"
                data-aos-easing="ease-in-sine"
              >
                <dd
                  class="mt-1 text-3xl font-semibold tracking-tight text-[#ff6600]"
                >
                  04
                </dd>
                <dt class="text-lg font-normal text-gray-900">
                  All LGN researchers are LPDP awardees. who are the best sons
                  and daughters of the nation who strongly committed to
                  contributing to solving the nation's various challenges
                </dt>
              </div>
            </dl>
          </div>
        </div>
      </div>
    </div>

    <div id="project" class="bg-white py-24 sm:py-32">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div
          class="mx-auto lg:mx-0"
          data-aos="fade-up"
          data-aos-duration="1000"
          data-aos-offset="50"
          data-aos-easing="ease-in-sine"
        >
          <p class="text-base font-semibold leading-7 text-[#ff6600]">
            Our Projects
          </p>
          <div class="flex flex-col sm:flex-row items-baseline sm:space-x-8">
            <h2
              class="mt-2 text-3xl sm:w-2/5 font-bold tracking-tight text-gray-900 sm:text-6xl"
            >
              Discover Our Selected Projects
            </h2>
            <p class="mt-6 sm:pl-20 sm:w-3/5 text-lg leading-8 text-gray-500">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Beatae
              hic ullam earum doloremque quo quia quae sapiente architecto quasi
              consectetur voluptates asperiores, ex dolores eveniet possimus ab!
            </p>
          </div>
        </div>
        <!-- <div
          class="mt-16 grid grid-cols-1 gap-x-8 gap-y-16 lg:grid-cols-3 lg:items-center px-1"
        > -->
        <dl class="mt-16 grid max-w-xl grid-cols-1 gap-x-8 gap-y-16 lg:max-w-none lg:grid-cols-3">
          <div class="flex flex-col">
            <dt class="text-lg font-bold leading-7 text-gray-900">
              <div class="mb-2 flex h-10 w-10 items-center justify-center rounded-lg bg-orange-500">
                <svg
                  class="h-6 w-6 text-white"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 13.5h3.86a2.25 2.25 0 012.012 1.244l.256.512a2.25 2.25 0 002.013 1.244h3.218a2.25 2.25 0 002.013-1.244l.256-.512a2.25 2.25 0 012.013-1.244h3.859m-19.5.338V18a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18v-4.162c0-.224-.034-.447-.1-.661L19.24 5.338a2.25 2.25 0 00-2.15-1.588H6.911a2.25 2.25 0 00-2.15 1.588L2.35 13.177a2.25 2.25 0 00-.1.661z" />
                </svg>
              </div>
              Unlimited inboxes
            </dt>
            <dd class="mt-1 flex flex-auto flex-col text-base leading-7 text-gray-500">
              <p class="flex-auto">
                Non quo aperiam repellendus quas est est. Eos aut dolore aut ut sit nesciunt. Ex tempora quia. Sit nobis consequatur dolores incidunt.
              </p>
            </dd>
          </div>
          <div class="flex flex-col">
            <dt class="text-lg font-bold leading-7 text-gray-900">
              <div class="mb-2 flex h-10 w-10 items-center justify-center rounded-lg bg-orange-500">
                <svg
                  class="h-6 w-6 text-white"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" d="M15 19.128a9.38 9.38 0 002.625.372 9.337 9.337 0 004.121-.952 4.125 4.125 0 00-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 018.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0111.964-3.07M12 6.375a3.375 3.375 0 11-6.75 0 3.375 3.375 0 016.75 0zm8.25 2.25a2.625 2.625 0 11-5.25 0 2.625 2.625 0 015.25 0z" />
                </svg>
              </div>
              Manage team members
            </dt>
            <dd class="mt-1 flex flex-auto flex-col text-base leading-7 text-gray-500">
              <p class="flex-auto">
                Vero eum voluptatem aliquid nostrum voluptatem. Vitae esse natus. Earum nihil deserunt eos quasi cupiditate. A inventore et molestiae natus.
              </p>
            </dd>
          </div>
          <div class="flex flex-col">
            <dt class="text-lg font-bold leading-7 text-gray-900">
              <div class="mb-2 flex h-10 w-10 items-center justify-center rounded-lg bg-orange-500">
                <svg
                  class="h-6 w-6 text-white"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path stroke-linecap="round" stroke-linejoin="round" d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0" />
                </svg>
              </div>
              Spam report
            </dt>
            <dd class="mt-1 flex flex-auto flex-col text-base leading-7 text-gray-500">
              <p class="flex-auto">
                Et quod quaerat dolorem quaerat architecto aliquam accusantium. Ex adipisci et doloremque autem quia quam. Quis eos molestiae at iure impedit.
              </p>
            </dd>
          </div>
        </dl>
        <!-- <article
            class="flex flex-col items-start justify-between"
            data-aos="fade-up"
            data-aos-duration="1000"
            data-aos-offset="0"
            data-aos-delay="200"
            data-aos-easing="ease-in-sine"
          >
            <div class="relative w-full">
              <img
                src="https://images.unsplash.com/photo-1580582932707-520aed937b7b?q=80&w=2832&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt=""
                class="aspect-[16/9] w-full bg-gray-100 object-cover sm:aspect-[2/1] lg:aspect-[3/2]"
              >
            </div>
            <div class="max-w-xl">
              <div class="group relative">
                <h3 class="mt-6 text-2xl font-semibold leading-6 text-gray-900">
                  Boost your conversion rate
                </h3>
                <p class="mt-4 line-clamp-3 text-sm leading-6 text-gray-600">
                  Illo sint voluptas. Error voluptates culpa eligendi. Hic vel
                  totam vitae illo. Non aliquid explicabo unde.
                </p>
              </div>
            </div>
          </article>
          <article
            class="flex flex-col items-start justify-between"
            data-aos="fade-up"
            data-aos-duration="1000"
            data-aos-offset="0"
            data-aos-delay="400"
            data-aos-easing="ease-in-sine"
          >
            <div class="relative w-full">
              <img
                src="https://images.unsplash.com/photo-1535978115060-d01ae6702684?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt=""
                class="aspect-[16/9] w-full bg-gray-100 object-cover sm:aspect-[2/1] lg:aspect-[3/2]"
              >
            </div>
            <div class="max-w-xl">
              <div class="group relative">
                <h3 class="mt-6 text-2xl font-semibold leading-6 text-gray-900">
                  Boost your conversion rate
                </h3>
                <p class="mt-4 line-clamp-3 text-sm leading-6 text-gray-600">
                  Illo sint voluptas. Error voluptates culpa eligendi. Hic vel
                  totam vitae illo. Non aliquid explicabo unde.
                </p>
              </div>
            </div>
          </article>
          <article
            class="flex flex-col items-start justify-between"
            data-aos="fade-up"
            data-aos-duration="1000"
            data-aos-offset="0"
            data-aos-delay="600"
            data-aos-easing="ease-in-sine"
          >
            <div class="relative w-full">
              <img
                src="https://images.unsplash.com/photo-1582213782179-e0d53f98f2ca?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                alt=""
                class="aspect-[16/9] w-full bg-gray-100 object-cover sm:aspect-[2/1] lg:aspect-[3/2]"
              >
            </div>
            <div class="max-w-xl">
              <div class="group relative">
                <h3 class="mt-6 text-2xl font-semibold leading-6 text-gray-900">
                  Boost your conversion rate
                </h3>
                <p class="mt-4 line-clamp-3 text-sm leading-6 text-gray-600">
                  Illo sint voluptas. Error voluptates culpa eligendi. Hic vel
                  totam vitae illo. Non aliquid explicabo unde.
                </p>
              </div>
            </div>
          </article> -->
        <!-- </div> -->
      </div>
    </div>

    <div id="teams" class="bg-gray-900 py-24 sm:py-32">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div
          class=""
          data-aos="fade-up"
          data-aos-duration="800"
          data-aos-offset="50"
          data-aos-easing="ease-in-sine"
        >
          <h2 class="text-base font-semibold leading-7 text-[#ff6600]">
            Our Team
          </h2>
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
            Meet Our Board of Director
          </h2>
          <p class="mt-4 text-lg leading-8 text-gray-400">
            A group of expert's to realize your idea.
          </p>
        </div>
        <ul
          role="list"
          class="mx-auto mt-2 grid max-w-2xl grid-cols-1 gap-6 sm:grid-cols-2 lg:mx-0 lg:max-w-none lg:grid-cols-3 lg:gap-8"
        >
          <li
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-offset="50"
            data-aos-delay="200"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-6 pt-12 sm:flex-row"
          >
            <img class="w-32 h-32 flex-none object-cover" src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?q=80&w=1587&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-lg font-semibold leading-8 tracking-tight text-white">
                Ansy Alghasi
              </h3>
              <p class="text-base leading-6 text-gray-600">
                CEO
              </p>
              <p class="text-base leading-7 text-gray-600">
                Universitas Bandung
              </p>
              <ul role="list" class="mt-4 flex items-center gap-x-6">
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
            data-aos-offset="50"
            data-aos-delay="400"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-6 pt-12 sm:flex-row"
          >
            <img class="w-32 h-32 flex-none object-cover" src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?q=80&w=1587&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-lg font-semibold leading-8 tracking-tight text-white">
                Ansy Alghasi
              </h3>
              <p class="text-base leading-6 text-gray-600">
                CEO
              </p>
              <p class="text-base leading-7 text-gray-600">
                Universitas Bandung
              </p>
              <ul role="list" class="mt-4 flex items-center gap-x-6">
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
            data-aos-offset="50"
            data-aos-delay="600"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-6 pt-12 sm:flex-row"
          >
            <img class="w-32 h-32 flex-none object-cover" src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?q=80&w=1587&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-lg font-semibold leading-8 tracking-tight text-white">
                Ansy Alghasi
              </h3>
              <p class="text-base leading-6 text-gray-600">
                CEO
              </p>
              <p class="text-base leading-7 text-gray-600">
                Universitas Bandung
              </p>
              <ul role="list" class="mt-4 flex items-center gap-x-6">
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
          <!-- <li
            class="relative group w-full h-auto aspect-3/4 overflow-hidden bg-gray-800"
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-offset="50"
            data-aos-delay="200"
            data-aos-easing="ease-in-sine"
          >
            <div class="mt-6 ml-6 absolute w-full flex flex-col items-start">
              <h3
                class="text-2xl text-left font-bold leading-7 tracking-tight text-white"
              >
                Ansy Alghasi
              </h3>
              <p class="text-sm leading-6 text-gray-400">
                CEO
              </p>
              <p class="text-sm font-medium leading-6 text-gray-400">
                Universitas Bandung
              </p>
            </div>
            <img
              class="absolute bottom-0 right-0 h-48 w-48 md:w-full md:h-full object-cover object-right-top"
              src="https://www.freeiconspng.com/thumbs/men-suit-png/men-suit-png-11.png"
              alt=""
            >
            <div
              class="relative h-96 invisible group-hover:visible transition ease-in-out hover:-translate-y-1 hover:scale-125 duration-700"
            >
              <div class="absolute w-full h-96 bg-black opacity-60" />
              <ul
                role="list"
                class="absolute w-full h-96 object-center flex items-center justify-center gap-x-6"
              >
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-8 w-8"
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
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">X</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">LinkedIn</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li
            class="relative group w-full h-auto aspect-3/4 overflow-hidden bg-gray-800"
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-offset="50"
            data-aos-delay="400"
            data-aos-easing="ease-in-sine"
          >
            <div class="mt-6 ml-6 absolute w-full flex flex-col items-start">
              <h3
                class="text-2xl text-left font-bold leading-7 tracking-tight text-white"
              >
                Megawati
              </h3>
              <p class="text-sm leading-6 text-gray-400">
                CMO
              </p>
              <p class="text-sm font-medium leading-6 text-gray-400">
                Universitas Bandung
              </p>
            </div>
            <img
              class="absolute bottom-0 right-0 h-48 w-48 md:w-full md:h-full object-cover object-right-top"
              src="https://www.freeiconspng.com/thumbs/men-suit-png/men-suit-png-11.png"
              alt=""
            >
            <div
              class="relative h-96 invisible group-hover:visible transition ease-in-out hover:-translate-y-1 hover:scale-125 duration-700"
            >
              <div class="absolute w-full h-96 bg-black opacity-60" />
              <ul
                role="list"
                class="absolute w-full h-96 object-center flex items-center justify-center gap-x-6"
              >
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-8 w-8"
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
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">X</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">LinkedIn</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li
            class="relative group w-full h-auto aspect-3/4 overflow-hidden bg-gray-800"
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-offset="50"
            data-aos-delay="600"
            data-aos-easing="ease-in-sine"
          >
            <div class="mt-6 ml-6 absolute w-full flex flex-col items-start">
              <h3
                class="text-2xl w-32 text-left font-bold leading-7 tracking-tight text-white"
              >
                Fitri N. Anggraeni
              </h3>
              <p class="text-sm leading-6 text-gray-400">
                Senior Designer
              </p>
              <p class="text-sm font-medium leading-6 text-gray-400">
                Universitas Bandung
              </p>
            </div>
            <img
              class="absolute bottom-0 right-0 h-48 w-48 md:w-full md:h-full object-cover object-right-top"
              src="https://www.freeiconspng.com/thumbs/men-suit-png/men-suit-png-11.png"
              alt=""
            >
            <div
              class="relative h-96 invisible group-hover:visible transition ease-in-out hover:-translate-y-1 hover:scale-125 duration-700"
            >
              <div class="absolute w-full h-96 bg-black opacity-60" />
              <ul
                role="list"
                class="absolute w-full h-96 object-center flex items-center justify-center gap-x-6"
              >
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-8 w-8"
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
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">X</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">LinkedIn</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li> -->
        </ul>
      </div>
    </div>

    <div class="bg-gray-900 pb-40">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div
          class=""
          data-aos="fade-up"
          data-aos-duration="800"
          data-aos-offset="50"
          data-aos-easing="ease-in-sine"
        >
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
            Meet Our Commissioner
          </h2>
        </div>
        <ul
          role="list"
          class="mx-auto mt-2 grid max-w-2xl grid-cols-1 gap-6 sm:grid-cols-2 lg:mx-0 lg:max-w-none lg:grid-cols-3 lg:gap-8"
        >
          <li
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-offset="50"
            data-aos-delay="200"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-6 pt-12 sm:flex-row"
          >
            <img class="w-32 h-32 flex-none object-cover" src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?q=80&w=1587&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-lg font-semibold leading-8 tracking-tight text-white">
                Ansy Alghasi
              </h3>
              <p class="text-base leading-6 text-gray-600">
                CEO
              </p>
              <p class="text-base leading-7 text-gray-600">
                Universitas Bandung
              </p>
              <ul role="list" class="mt-4 flex items-center gap-x-6">
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
            data-aos-offset="50"
            data-aos-delay="400"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-6 pt-12 sm:flex-row"
          >
            <img class="w-32 h-32 flex-none object-cover" src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?q=80&w=1587&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-lg font-semibold leading-8 tracking-tight text-white">
                Ansy Alghasi
              </h3>
              <p class="text-base leading-6 text-gray-600">
                CEO
              </p>
              <p class="text-base leading-7 text-gray-600">
                Universitas Bandung
              </p>
              <ul role="list" class="mt-4 flex items-center gap-x-6">
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
            data-aos-offset="50"
            data-aos-delay="600"
            data-aos-easing="ease-in-sine"
            class="flex flex-col gap-6 pt-12 sm:flex-row"
          >
            <img class="w-32 h-32 flex-none object-cover" src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?q=80&w=1587&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
            <div class="max-w-xl flex-auto">
              <h3 class="text-lg font-semibold leading-8 tracking-tight text-white">
                Ansy Alghasi
              </h3>
              <p class="text-base leading-6 text-gray-600">
                CEO
              </p>
              <p class="text-base leading-7 text-gray-600">
                Universitas Bandung
              </p>
              <ul role="list" class="mt-4 flex items-center gap-x-6">
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
          <!-- <li
            class="relative group w-full h-auto aspect-3/4 overflow-hidden bg-gray-800"
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-offset="50"
            data-aos-delay="200"
            data-aos-easing="ease-in-sine"
          >
            <div class="mt-6 ml-6 absolute w-full flex flex-col items-start">
              <h3
                class="text-2xl text-left font-bold leading-7 tracking-tight text-white"
              >
                Ansy Alghasi
              </h3>
              <p class="text-sm leading-6 text-gray-400">
                CEO
              </p>
              <p class="text-sm font-medium leading-6 text-gray-400">
                Universitas Bandung
              </p>
            </div>
            <img
              class="absolute bottom-0 right-0 h-48 w-48 md:w-full md:h-full object-cover object-right-top"
              src="https://www.freeiconspng.com/thumbs/men-suit-png/men-suit-png-11.png"
              alt=""
            >
            <div
              class="relative h-96 invisible group-hover:visible transition ease-in-out hover:-translate-y-1 hover:scale-125 duration-700"
            >
              <div class="absolute w-full h-96 bg-black opacity-60" />
              <ul
                role="list"
                class="absolute w-full h-96 object-center flex items-center justify-center gap-x-6"
              >
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-8 w-8"
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
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">X</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">LinkedIn</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li
            class="relative group w-full h-auto aspect-3/4 overflow-hidden bg-gray-800"
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-offset="50"
            data-aos-delay="400"
            data-aos-easing="ease-in-sine"
          >
            <div class="mt-6 ml-6 absolute w-full flex flex-col items-start">
              <h3
                class="text-2xl text-left font-bold leading-7 tracking-tight text-white"
              >
                Megawati
              </h3>
              <p class="text-sm leading-6 text-gray-400">
                CMO
              </p>
              <p class="text-sm font-medium leading-6 text-gray-400">
                Universitas Bandung
              </p>
            </div>
            <img
              class="absolute bottom-0 right-0 h-48 w-48 md:w-full md:h-full object-cover object-right-top"
              src="https://www.freeiconspng.com/thumbs/men-suit-png/men-suit-png-11.png"
              alt=""
            >
            <div
              class="relative h-96 invisible group-hover:visible transition ease-in-out hover:-translate-y-1 hover:scale-125 duration-700"
            >
              <div class="absolute w-full h-96 bg-black opacity-60" />
              <ul
                role="list"
                class="absolute w-full h-96 object-center flex items-center justify-center gap-x-6"
              >
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-8 w-8"
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
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">X</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">LinkedIn</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li
            class="relative group w-full h-auto aspect-3/4 overflow-hidden bg-gray-800"
            data-aos="fade-up"
            data-aos-duration="800"
            data-aos-offset="50"
            data-aos-delay="600"
            data-aos-easing="ease-in-sine"
          >
            <div class="mt-6 ml-6 absolute w-full flex flex-col items-start">
              <h3
                class="text-2xl w-32 text-left font-bold leading-7 tracking-tight text-white"
              >
                Fitri N. Anggraeni
              </h3>
              <p class="text-sm leading-6 text-gray-400">
                Senior Designer
              </p>
              <p class="text-sm font-medium leading-6 text-gray-400">
                Universitas Bandung
              </p>
            </div>
            <img
              class="absolute bottom-0 right-0 h-48 w-48 md:w-full md:h-full object-cover object-right-top"
              src="https://www.freeiconspng.com/thumbs/men-suit-png/men-suit-png-11.png"
              alt=""
            >
            <div
              class="relative h-96 invisible group-hover:visible transition ease-in-out hover:-translate-y-1 hover:scale-125 duration-700"
            >
              <div class="absolute w-full h-96 bg-black opacity-60" />
              <ul
                role="list"
                class="absolute w-full h-96 object-center flex items-center justify-center gap-x-6"
              >
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">Instagram</span>
                    <svg
                      class="h-8 w-8"
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
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">X</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        d="M11.4678 8.77491L17.2961 2H15.915L10.8543 7.88256L6.81232 2H2.15039L8.26263 10.8955L2.15039 18H3.53159L8.87581 11.7878L13.1444 18H17.8063L11.4675 8.77491H11.4678ZM9.57608 10.9738L8.95678 10.0881L4.02925 3.03974H6.15068L10.1273 8.72795L10.7466 9.61374L15.9156 17.0075H13.7942L9.57608 10.9742V10.9738Z"
                      />
                    </svg>
                  </a>
                </li>
                <li>
                  <a href="#" class="text-white hover:text-[#ff6600]">
                    <span class="sr-only">LinkedIn</span>
                    <svg
                      class="h-8 w-8"
                      fill="currentColor"
                      viewBox="0 0 20 20"
                      aria-hidden="true"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </a>
                </li>
              </ul>
            </div>
          </li> -->
        </ul>
      </div>
    </div>

    <div id="client" class="bg-white pt-24">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div class="mx-auto max-w-2xl lg:max-w-none">
          <h2 class="text-lg font-semibold leading-8 text-gray-900">
            Trusted by the world’s most innovative teams
          </h2>

          <Slider class="mt-8" />
        </div>
      </div>
    </div>

    <div class="relative isolate bg-white">
      <div class="mx-auto grid max-w-7xl grid-cols-1 lg:grid-cols-2">
        <div
          class="relative px-6 pb-20 pt-24 sm:pt-32 lg:static lg:px-8 lg:py-48"
          data-aos="fade-right"
          data-aos-duration="800"
          data-aos-offset="50"
          data-aos-delay="200"
          data-aos-easing="ease-in-sine"
        >
          <div class="mx-auto max-w-xl lg:mx-0 lg:max-w-lg">
            <div
              class="absolute inset-y-0 left-0 -z-10 w-full overflow-hidden lg:w-1/2"
            />

            <h2 class="text-base font-semibold leading-7 text-[#ff6600]">
              Let’s Talk
            </h2>
            <h2 class="text-3xl font-bold tracking-tight text-gray-900">
              Get In Touch With Us
            </h2>
            <p class="mt-6 text-lg leading-8 text-gray-600">
              Let’s create higher quality of policy and analysis with LGN.
            </p>
            <dl class="mt-10 space-y-4 text-base leading-7 text-gray-600">
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
                  RT.10/RW.2, Rw. Buaya, Kecamatan Cengkareng, Kota Jakarta
                  Barat, Daerah KhususIbukota Jakarta 11740
                </dd>
              </div>
              <div class="flex gap-x-4">
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
          action="#"
          method="POST"
          class="px-6 pb-24 pt-20 sm:pb-32 lg:px-8 lg:py-48"
          data-aos="fade-left"
          data-aos-duration="800"
          data-aos-offset="50"
          data-aos-delay="200"
          data-aos-easing="ease-in-sine"
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
                    type="name"
                    name="name"
                    autocomplete="name"
                    class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                  >
                </div>
              </div>
              <div class="sm:col-span-2">
                <label
                  for="email"
                  class="block text-sm font-semibold leading-6 text-gray-900"
                >Email</label>
                <div class="mt-2.5">
                  <input
                    id="email"
                    type="email"
                    name="email"
                    autocomplete="email"
                    class="block w-full rounded-md border-0 px-3.5 py-2 text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 placeholder:text-gray-400 focus:ring-2 focus:ring-inset focus:ring-indigo-600 sm:text-sm sm:leading-6"
                  >
                </div>
              </div>
              <div class="sm:col-span-2">
                <label
                  for="phone-number"
                  class="block text-sm font-semibold leading-6 text-gray-900"
                >Phone number</label>
                <div class="mt-2.5">
                  <input
                    id="phone-number"
                    type="tel"
                    name="phone-number"
                    autocomplete="tel"
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
                    name="message"
                    rows="4"
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
  mounted () {
    AOS.init({
    })
  }
}
</script>
