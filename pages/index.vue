<!-- Please remove this file from your project -->
<template>
  <div>
    <div class="bg-white">
      <header class="absolute inset-x-0 top-0 z-50">
        <nav
          class="flex items-center justify-between p-6 lg:px-16"
          aria-label="Global"
        >
          <div class="flex lg:flex-1">
            <a href="#" class="-m-1.5 p-1.5 flex space-x-2 items-center">
              <span class="sr-only">Your Company</span>
              <div class="w-12 h-12 rounded-full bg-[#ff6600]" />
              <span class="font-bold text-2xl">LensaGaruda</span>
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
          <div class="hidden lg:flex lg:gap-x-12">
            <a
              href="#"
              class="text-sm font-semibold leading-6 text-gray-900"
            >About Us</a>
            <a
              href="#"
              class="text-sm font-semibold leading-6 text-gray-900"
            >Service</a>
            <a
              href="#"
              class="text-sm font-semibold leading-6 text-gray-900"
            >Why LGN?</a>
            <a
              href="#"
              class="text-sm font-semibold leading-6 text-gray-900"
            >Client</a>
            <a
              href="#"
              class="text-sm font-semibold leading-6 text-gray-900"
            >Teams</a>
          </div>
          <div class="hidden lg:flex lg:flex-1 lg:justify-end">
            <a
              href="#"
              class="text-sm font-semibold leading-6 text-white bg-[#ff6600] px-4 py-2"
            >Let's Talk <span aria-hidden="true">&rarr;</span></a>
          </div>
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
          class="mt-16 mx-auto max-w-7xl px-6 py-24 sm:py-32 lg:grid lg:grid-cols-7 lg:items-center lg:gap-x-0 lg:px-0 lg:py-10"
        >
          <div class="col-span-5 mx-auto lg:mx-0 lg:flex-auto">
            <h1
              class="text-4xl font-bold tracking-tight text-gray-900 sm:text-7xl mr-4"
            >
              Intelligent Solution for Higher Quality
              <span class="text-[#ff6600]">Policy</span>
            </h1>
          </div>
          <div class="relative col-span-2 mx-auto lg:mx-0">
            <h1
              class="text-4xl font-normal tracking-tight text-gray-900 sm:text-3xl absolute inset-0"
            >
              A tailor-made service. We have the people you need.
            </h1>
          </div>
        </div>
        <div
          class="mx-auto max-w-7xl px-6 py-24 sm:py-32 lg:grid lg:grid-cols-7 lg:items-center lg:gap-x-0 lg:px-0 lg:py-0"
        >
          <div class="col-span-5 mx-auto lg:mx-0 lg:flex-auto">
            <img
              class="w-full h-56 object-cover pr-8"
              data-aos="fade-left"
              src="https://images.unsplash.com/photo-1550592704-6c76defa9985?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            >
          </div>
          <div class="relative col-span-2 mx-auto lg:mx-0 bg-[#ff6600]">
            <div class="grid grid-cols-2">
              <div class="flex flex-col text-white text-center px-8 py-10">
                <h3 class="text-4xl font-bold">
                  40 +
                </h3>
                <h3 class="mt-2 leading-5">
                  Company Clients of Fellows LGN
                </h3>
              </div>
              <div class="flex flex-col text-white text-center px-8 py-10">
                <h3 class="text-4xl font-bold">
                  7 +
                </h3>
                <h3 class="mt-2 leading-5">
                  Recent Portfolios
                </h3>
              </div>
            </div>
          </div>
        </div>
        <div
          class="mx-auto max-w-7xl px-6 py-24 sm:py-32 lg:grid lg:grid-cols-7 lg:items-center lg:gap-x-0 lg:px-0 lg:py-0"
        >
          <div class="relative col-span-2 mx-auto lg:mx-0 bg-[#ff6600]">
            <div class="flex flex-col text-white text-center px-8 py-14">
              <h3 class="text-3xl font-bold">
                Get Started<span class="ml-4" aria-hidden="true">&rarr;</span>
              </h3>
            </div>
          </div>
          <div class="col-span-5 mx-auto lg:mx-0 lg:flex-auto">
            <img
              class="w-full h-56 object-cover pl-8"
              src="https://images.unsplash.com/photo-1515378960530-7c0da6231fb1?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            >
          </div>
        </div>
      </div>
    </div>

    <div class="overflow-hidden bg-white py-24 sm:py-32">
      <div class="mx-auto max-w-7xl md:px-6 lg:px-0">
        <div
          class="grid grid-cols-1 gap-x-16 gap-y-16 sm:gap-y-20 lg:grid-cols-2 lg:items-center"
        >
          <div class="sm:px-6 lg:px-0">
            <div
              class="relative isolate overflow-hidden bg-[#ff6600] px-6 pt-8 sm:mx-auto sm:max-w-2xl sm:pl-16 sm:pr-0 sm:pt-16 lg:mx-0 lg:max-w-none"
            >
              <div
                class="absolute -inset-y-px -left-3 -z-10 w-full origin-bottom-left skew-x-[-30deg] bg-indigo-100 opacity-20 ring-1 ring-inset ring-white"
                aria-hidden="true"
              />
              <div class="mx-auto max-w-2xl sm:mx-0 sm:max-w-none">
                <img
                  src="https://tailwindui.com/img/component-images/project-app-screenshot.png"
                  alt="Product screenshot"
                  width="2432"
                  height="1442"
                  class="-mb-12 w-[57rem] max-w-none bg-gray-800 ring-1 ring-white/10"
                >
              </div>
              <div
                class="pointer-events-none absolute inset-0 ring-1 ring-inset ring-black/10"
                aria-hidden="true"
              />
            </div>
          </div>
          <div class="px-6 lg:px-0 lg:pr-4 lg:pt-0">
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

    <div class="bg-white py-24 sm:py-32">
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div class="mx-auto lg:mx-0">
          <p class="text-base font-semibold leading-7 text-[#ff6600]">
            Our Service
          </p>
          <div class="flex items-baseline">
            <h2
              class="mt-2 text-4xl w-2/5 font-bold tracking-tight text-gray-900 sm:text-6xl"
            >
              What Services We're Offering
            </h2>
            <p class="mt-6 w-3/5 text-lg leading-8 text-gray-500">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Beatae
              hic ullam earum doloremque quo quia quae sapiente architecto quasi
              consectetur voluptates asperiores, ex dolores eveniet possimus ab!
              Natus, ullam laudantium.
            </p>
          </div>
        </div>
        <div class="mt-16 grid grid-cols-1 divide-y">
          <div>
            <h1
              class="py-8 text-4xl font-medium tracking-tight text-gray-900 sm:text-2xl"
            >
              Consulting Services in Public Policy
            </h1>
          </div>
          <div>
            <h1
              class="py-8 text-4xl font-medium tracking-tight text-gray-900 sm:text-2xl"
            >
              3rd Party Researchers, Surveyors, and Data Providers
            </h1>
          </div>
          <div>
            <h1
              class="py-8 text-4xl font-medium tracking-tight text-gray-900 sm:text-2xl"
            >
              Advisory Services from Experts and Thought Leaders
            </h1>
          </div>
        </div>
      </div>
    </div>

    <div class="overflow-hidden bg-white py-24 sm:py-32">
      <div class="mx-auto max-w-7xl md:px-6 lg:px-0">
        <div
          class="grid grid-cols-1 gap-x-16 gap-y-16 sm:gap-y-20 lg:grid-cols-2 lg:items-center"
        >
          <div class="sm:px-6 lg:px-0">
            <div
              class="relative isolate overflow-hidden bg-[#ff6600] px-6 pt-8 sm:mx-auto sm:max-w-2xl sm:pl-16 sm:pr-0 sm:pt-16 lg:mx-0 lg:max-w-none"
            >
              <div
                class="absolute -inset-y-px -left-3 -z-10 w-full origin-bottom-left skew-x-[-30deg] bg-indigo-100 opacity-20 ring-1 ring-inset ring-white"
                aria-hidden="true"
              />
              <div class="mx-auto max-w-2xl sm:mx-0 sm:max-w-none">
                <img
                  src="https://images.unsplash.com/photo-1499914485622-a88fac536970?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                  alt="Product screenshot"
                  width="2432"
                  height="1442"
                  class="-mb-12 w-[57rem] max-w-none bg-gray-800 ring-1 ring-white/10"
                >
              </div>
              <div
                class="pointer-events-none absolute inset-0 ring-1 ring-inset ring-black/10"
                aria-hidden="true"
              />
            </div>
          </div>
          <div class="px-6 lg:px-0 lg:pr-4 lg:pt-0">
            <div class="mx-auto max-w-2xl lg:mx-0 lg:max-w-lg">
              <h2 class="text-base font-semibold leading-7 text-[#ff6600]">
                Why Choose Us
              </h2>
              <p
                class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-5xl"
              >
                Why You Should Choose LensaGaruda
              </p>
              <dl class="mt-5 grid grid-cols-1 gap-2">
                <div class="py-2">
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
                <div class="py-2">
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
                <div class="py-2">
                  <dd
                    class="mt-1 text-3xl font-semibold tracking-tight text-[#ff6600]"
                  >
                    03
                  </dd>
                  <dt class="text-lg font-normal text-gray-900">
                    LGN's research is not only academic in nature but is
                    oriented towards practical policy recommendations that are
                    more useful for the government in carry out policy execution
                  </dt>
                </div>
                <div class="py-2">
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
    </div>

    <div class="bg-gray-900 py-24 sm:py-32">
      <div class="mx-auto max-w-7xl px-6 text-center lg:px-8">
        <div class="mx-auto max-w-2xl">
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
          class="mx-auto mt-20 grid max-w-2xl grid-cols-1 gap-6 sm:grid-cols-2 lg:mx-0 lg:max-w-none lg:grid-cols-3 lg:gap-8"
        >
          <li class="relative group h-96 overflow-hidden bg-gray-800">
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
          <li class="relative group h-96 overflow-hidden bg-gray-800">
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
          <li class="relative group h-96 overflow-hidden bg-gray-800">
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
          </li>
        </ul>
      </div>
    </div>

    <div class="bg-gray-900 pb-24">
      <div class="mx-auto max-w-7xl px-6 text-center lg:px-8">
        <div class="mx-auto max-w-2xl">
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
            Meet Our Commissioner
          </h2>
        </div>
        <ul
          role="list"
          class="mx-auto mt-20 grid max-w-2xl grid-cols-1 gap-6 sm:grid-cols-2 lg:mx-0 lg:max-w-none lg:grid-cols-3 lg:gap-8"
        >
          <li class="relative group h-96 overflow-hidden bg-gray-800">
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
          <li class="relative group h-96 overflow-hidden bg-gray-800">
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
          <li class="relative group h-96 overflow-hidden bg-gray-800">
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
          </li>
        </ul>
      </div>
    </div>

    <div class="relative isolate bg-white">
      <div class="mx-auto grid max-w-7xl grid-cols-1 lg:grid-cols-2">
        <div
          class="relative px-6 pb-20 pt-24 sm:pt-32 lg:static lg:px-8 lg:py-48"
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
                    href="tel:+1 (555) 234-5678"
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
                    href="mailto:hello@example.com"
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
                class="rounded-md bg-[#ff6600] px-3.5 py-2.5 text-center text-sm font-semibold text-white shadow-sm hover:bg-orange-600 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
              >
                Send message
              </button>
            </div>
          </div>
        </form>
      </div>
    </div>

    <footer class="bg-gray-900" aria-labelledby="footer-heading">
      <h2 id="footer-heading" class="sr-only">
        Footer
      </h2>
      <div class="mx-auto max-w-7xl px-6 pb-8 pt-16 lg:px-8">
        <p class="text-center mx-auto text-4xl text-white">
          Please feel free to get in touch with us
        </p>
        <div class="pt-8 lg:flex lg:items-center lg:justify-between">
          <dl
            class="mt-10 grid grid-cols-1 md:grid-cols-3 gap-x-16 text-base leading-7 text-gray-600 mx-auto"
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
                  href="tel:+1 (555) 234-5678"
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
                  href="mailto:hello@example.com"
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
