<template>
  <div class="h-screen flex flex-col antialiased">
    <header class="flex flex-shrink-0">
      <div class="w-64 flex-shrink-0 px-4 py-3 bg-gray-800">
        <button class="block w-full flex items-center focus:outline-none">
          <img
            class="h-8 w-8 rounded-full"
            src="../assets/profile.jpg"
            alt="profile"
          />
          <span class="ml-4 text-sm font-medium text-white">Benn Ajax</span>
          <svg
            class="h-4 w-4 ml-auto stroke-current text-gray-400"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </button>
      </div>
      <div class="flex-1 bg-gray-700 flex justify-between items-center px-6">
        <nav class="flex">
          <router-link
            to="#"
            class="
              inline-block
              px-3
              py-2
              bg-gray-800
              rounded-lg
              leading-none
              text-sm
              font-medium
              text-white
            "
            >Mailbox</router-link
          >
          <router-link
            to="#"
            class="
              inline-block
              ml-2
              px-3
              py-2
              rounded-lg
              leading-none
              text-sm
              font-medium
              text-white
              hover:bg-gray-600
            "
            >Customers</router-link
          >
          <router-link
            to="#"
            class="
              inline-block
              ml-2
              px-3
              py-2
              rounded-lg
              leading-none
              text-sm
              font-medium
              text-white
              hover:bg-gray-600
            "
            >Reporting</router-link
          >
          <router-link
            to="#"
            class="
              inline-block
              ml-2
              px-3
              py-2
              rounded-lg
              leading-none
              text-sm
              font-medium
              text-white
              hover:bg-gray-600
            "
            >Manage</router-link
          >
        </nav>
        <div class="flex items-center">
          <div class="relative w-64">
            <span class="absolute inset-y-0 left-0 flex items-center pl-2">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5 text-gray-400"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                  clip-rule="evenodd"
                />
              </svg>
            </span>
            <input
              type="text"
              class="
                block
                pl-9
                pr-4
                py-1.5
                w-full
                bg-gray-900
                rounded-lg
                text-sm
                placeholder-gray-400
                text-white
                focus:outline-none
                focus:bg-white
                focus:text-gray-900
              "
              placeholder="Search"
            />
          </div>
          <button
            type="button"
            class="ml-5 text-gray-400 hover:text-gray-200 focus:outline-none"
          >
            <svg
              class="h-6 w-6 stroke-current"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
              />
            </svg>
          </button>
          <button
            type="button"
            class="ml-5 text-gray-400 hover:text-gray-200 focus:outline-none"
          >
            <svg
              class="h-6 w-6 stroke-current"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M8.228 9c.549-1.165 2.03-2 3.772-2 2.21 0 4 1.343 4 3 0 1.4-1.278 2.575-3.006 2.907-.542.104-.994.54-.994 1.093m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
              />
            </svg>
          </button>
        </div>
      </div>
    </header>
    <div class="flex flex-1 overflow-y-hidden">
      <aside class="w-64 p-6 bg-gray-100 overflow-y-auto scrollbar scrollbar-thin scrollbar-thumb-gray-400 scrollbar-thumb-rounded-md scrollbar-track-gray-100">
        <nav>
          <h2
            class="text-xs font-semibold text-gray-600 uppercase tracking-wide"
          >
            Mailboxes
          </h2>
          <div class="mt-3">
            <router-link
              to="#"
              class="
                -mx-3
                px-3
                py-2
                flex
                justify-between
                items-center
                font-medium
                text-sm
                bg-gray-200
                rounded-lg
              "
            >
              <span class="inline-flex">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 stroke-current text-gray-600"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M20 13V6a2 2 0 00-2-2H6a2 2 0 00-2 2v7m16 0v5a2 2 0 01-2 2H6a2 2 0 01-2-2v-5m16 0h-2.586a1 1 0 00-.707.293l-2.414 2.414a1 1 0 01-.707.293h-3.172a1 1 0 01-.707-.293l-2.414-2.414A1 1 0 006.586 13H4"
                  />
                </svg>
                <span class="ml-2 text-gray-900"> Inbox </span>
              </span>
              <span
                class="
                  inline-block
                  w-9
                  text-center
                  py-1
                  leading-none
                  text-xs
                  font-semibold
                  text-gray-700
                  bg-gray-300
                  rounded-full
                "
              >
                6
              </span>
            </router-link>
            <router-link
              to="#"
              class="
                mt-2
                -mx-3
                px-3
                py-2
                flex
                justify-between
                items-center
                font-medium
                text-sm
                hover:bg-gray-200
                rounded-lg
              "
            >
              <span class="inline-flex">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 stroke-current text-gray-500"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"
                  />
                </svg>

                <span class="ml-2 text-gray-900"> Flagged </span>
              </span>
              <span
                class="
                  hidden
                  inline-block
                  w-9
                  text-center
                  py-1
                  leading-none
                  text-xs
                  font-semibold
                  text-gray-700
                  bg-gray-300
                  rounded-full
                "
              >
                6
              </span>
            </router-link>
            <router-link
              to="#"
              class="
                mt-2
                -mx-3
                px-3
                py-2
                flex
                justify-between
                items-center
                font-medium
                text-sm
                hover:bg-gray-200
                rounded-lg
              "
            >
              <span class="inline-flex">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 stroke-current text-gray-500"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"
                  />
                </svg>

                <span class="ml-2 text-gray-900"> Drafts </span>
              </span>
              <span
                class="
                  inline-block
                  w-9
                  text-center
                  py-1
                  leading-none
                  text-xs
                  font-semibold
                  text-gray-700
                  bg-gray-300
                  rounded-full
                "
              >
                2
              </span>
            </router-link>
            <router-link
              to="#"
              class="
                mt-2
                -mx-3
                px-3
                py-2
                flex
                justify-between
                items-center
                font-medium
                text-sm
                hover:bg-gray-200
                rounded-lg
              "
            >
              <span class="inline-flex">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 stroke-current text-gray-500"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M5.121 17.804A13.937 13.937 0 0112 16c2.5 0 4.847.655 6.879 1.804M15 10a3 3 0 11-6 0 3 3 0 016 0zm6 2a9 9 0 11-18 0 9 9 0 0118 0z"
                  />
                </svg>

                <span class="ml-2 text-gray-900"> Assigned </span>
              </span>
              <span
                class="
                  inline-block
                  w-9
                  text-center
                  py-1
                  leading-none
                  text-xs
                  font-semibold
                  text-gray-700
                  bg-gray-300
                  rounded-full
                "
              >
                1
              </span>
            </router-link>
            <router-link
              to="#"
              class="
                mt-2
                -mx-3
                px-3
                py-2
                flex
                justify-between
                items-center
                font-medium
                text-sm
                hover:bg-gray-200
                rounded-lg
              "
            >
              <span class="inline-flex">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 stroke-current text-gray-500"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"
                  />
                </svg>

                <span class="ml-2 text-gray-900"> Closed </span>
              </span>
              <span
                class="
                  hidden
                  inline-block
                  w-9
                  text-center
                  py-1
                  leading-none
                  text-xs
                  font-semibold
                  text-gray-700
                  bg-gray-300
                  rounded-full
                "
              >
                6
              </span>
            </router-link>
            <router-link
              to="#"
              class="
                mt-2
                -mx-3
                px-3
                py-2
                flex
                justify-between
                items-center
                font-medium
                text-sm
                hover:bg-gray-200
                rounded-lg
              "
            >
              <span class="inline-flex">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5 stroke-current text-gray-500"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M5 8h14M5 8a2 2 0 110-4h14a2 2 0 110 4M5 8v10a2 2 0 002 2h10a2 2 0 002-2V8m-9 4h4"
                  />
                </svg>
                <span class="ml-2 text-gray-900"> Trash </span>
              </span>
              <span
                class="
                  hidden
                  inline-block
                  w-9
                  text-center
                  py-1
                  leading-none
                  text-xs
                  font-semibold
                  text-gray-700
                  bg-gray-300
                  rounded-full
                "
              >
                6
              </span>
            </router-link>
          </div>

          <h2
            class="
              mt-8
              text-xs
              font-semibold
              text-gray-600
              uppercase
              tracking-wide
            "
          >
            Folders
          </h2>

          <div class="mt-4">
            <router-link
              to="#"
              class="block text-sm mt-4 font-medium text-gray-700"
            >
              Refunds
            </router-link>
            <router-link
              to="#"
              class="block text-sm mt-4 font-medium text-gray-700"
            >
              Discounts
            </router-link>
            <router-link
              to="#"
              class="block text-sm mt-4 font-medium text-gray-700"
            >
              Bugs
            </router-link>
          </div>
        </nav>
      </aside>
      <main class="flex flex-1 bg-gray-200">
        <div class="flex flex-col w-full max-w-xs flex-grow border-l border-r">
          <div class="flex-shrink-0 px-4 py-2 border-b flex items-center justify-between">
            <button
              type="button"
              class="flex items-end text-xs font-semibold text-gray-600 focus:outline-none"
            >
              Sort by Date
              <span class="ml-1.5">
                <svg
                  class="h-3.5 w-3.5 ml-auto stroke-current text-gray-500"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M19 9l-7 7-7-7"
                  />
                </svg>
              </span>
            </button>
            <button type="button" class="focus:outline-none">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 text-gray-500"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 4h13M3 8h9m-9 4h6m4 0l4-4m0 0l4 4m-4-4v12"
                />
              </svg>
            </button>
          </div>
          <div class="flex-1 overflow-y-auto scrollbar scrollbar-thin scrollbar-thumb-gray-400 scrollbar-thumb-rounded-md scrollbar-track-gray-100">
            <router-link to="#" class="block px-6 pt-3 pb-4 bg-white">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">Gloria Roberson</span>
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">Refund</p>
              <p class="mt-2 text-sm text-gray-600">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos sequi voluptas...</p>
            </router-link>
            <router-link to="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">Gloria Roberson</span>
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">Refund</p>
              <p class="mt-2 text-sm text-gray-600">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos sequi voluptas...</p>
            </router-link>
            <router-link to="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">Gloria Roberson</span>
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">Refund</p>
              <p class="mt-2 text-sm text-gray-600">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos sequi voluptas...</p>
            </router-link>
            <router-link to="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">Gloria Roberson</span>
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">Refund</p>
              <p class="mt-2 text-sm text-gray-600">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos sequi voluptas...</p>
            </router-link>
            <router-link to="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">Gloria Roberson</span>
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">Refund</p>
              <p class="mt-2 text-sm text-gray-600">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos sequi voluptas...</p>
            </router-link>
            <router-link to="#" class="block px-6 pt-3 pb-4 bg-white border-t">
              <div class="flex justify-between">
                <span class="text-sm font-semibold text-gray-900">Gloria Roberson</span>
                <span class="text-sm text-gray-600">2 days ago</span>
              </div>
              <p class="text-sm text-gray-900">Refund</p>
              <p class="mt-2 text-sm text-gray-600">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quos sequi voluptas...</p>
            </router-link>
          </div>
        </div>
        <div class="flex flex-1 bg-green-600"></div>
      </main>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
};
</script>
