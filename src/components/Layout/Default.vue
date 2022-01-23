<template>
  <div class="flex flex-row">
    <!-- Sidebar -->
    <aside
      class="px-4 hidden lg:block flex-shrink-0 w-64 text-gray-200 bg-gray-800"
    >
      <div>
        <h2 class="py-2 flex items-center text-3xl text-white font-semibold">
          <span>
            <svg
              class="w-12 h-12 text-white"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M13.25 9.703H16.25V9.203H13.25V9.703ZM15.788 12.294H13.727V12.284C13.727 11.666 14.139 11.188 14.765 11.188C15.385 11.188 15.788 11.661 15.788 12.284V12.294ZM14.755 10.297C13.401 10.297 12.475 11.134 12.475 12.549V12.99C12.475 14.469 13.396 15.297 14.808 15.297C16.186 15.297 16.855 14.527 16.977 13.754H15.793C15.686 14.146 15.327 14.382 14.818 14.382C14.168 14.382 13.727 13.918 13.727 13.186V13.054H17.025V12.58C17.025 11.192 16.157 10.297 14.755 10.297ZM9.219 14.237H8.26V12.304H9.487C10.244 12.304 10.657 12.68 10.657 13.294C10.657 13.913 10.24 14.237 9.219 14.237ZM8.26 9.67H9.405C10.01 9.67 10.364 9.994 10.364 10.522C10.364 11.089 9.981 11.408 9.113 11.408H8.26V9.67ZM10.518 11.784V11.728C11.165 11.57 11.64 11.094 11.64 10.304C11.64 9.309 10.873 8.703 9.703 8.703H6.975V15.203H9.698C11.026 15.203 11.975 14.532 11.975 13.37C11.975 12.395 11.304 11.86 10.518 11.784ZM12 20C7.589 20 4 16.411 4 12C4 7.589 7.589 4 12 4C16.411 4 20 7.589 20 12C20 16.411 16.411 20 12 20ZM12 2C6.486 2 2 6.486 2 12C2 17.514 6.486 22 12 22C17.514 22 22 17.514 22 12C22 6.486 17.514 2 12 2Z"
                fill="#757D8A"
              />
            </svg>
          </span>
          <span>Dash</span>
        </h2>
      </div>
      <div
        class="
          fixed
          inset-y-0
          left-0
          w-64
          top-[55px]
          overflow-hidden
          hover:overflow-y-auto
          bg-gray-800
        "
      >
        <div class="px-6">
          <div class="my-8 flex flex-col">
            <h3 class="text-sm font-semibold">Menu</h3>
            <!-- link-group-1 -->
            <div class="menu-1">
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10.496 2.132a1 1 0 00-.992 0l-7 4A1 1 0 003 8v7a1 1 0 100 2h14a1 1 0 100-2V8a1 1 0 00.496-1.868l-7-4zM6 9a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1zm3 1a1 1 0 012 0v3a1 1 0 11-2 0v-3zm5-1a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Inventory</span
                >
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M2 5a2 2 0 012-2h12a2 2 0 012 2v10a2 2 0 01-2 2H4a2 2 0 01-2-2V5zm3.293 1.293a1 1 0 011.414 0l3 3a1 1 0 010 1.414l-3 3a1 1 0 01-1.414-1.414L7.586 10 5.293 7.707a1 1 0 010-1.414zM11 12a1 1 0 100 2h3a1 1 0 100-2h-3z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Inventory</span
                >
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 1.944A11.954 11.954 0 012.166 5C2.056 5.649 2 6.319 2 7c0 5.225 3.34 9.67 8 11.317C14.66 16.67 18 12.225 18 7c0-.682-.057-1.35-.166-2.001A11.954 11.954 0 0110 1.944zM11 14a1 1 0 11-2 0 1 1 0 012 0zm0-7a1 1 0 10-2 0v3a1 1 0 102 0V7z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Inventory</span
                >
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M6.672 1.911a1 1 0 10-1.932.518l.259.966a1 1 0 001.932-.518l-.26-.966zM2.429 4.74a1 1 0 10-.517 1.932l.966.259a1 1 0 00.517-1.932l-.966-.26zm8.814-.569a1 1 0 00-1.415-1.414l-.707.707a1 1 0 101.415 1.415l.707-.708zm-7.071 7.072l.707-.707A1 1 0 003.465 9.12l-.708.707a1 1 0 001.415 1.415zm3.2-5.171a1 1 0 00-1.3 1.3l4 10a1 1 0 001.823.075l1.38-2.759 3.018 3.02a1 1 0 001.414-1.415l-3.019-3.02 2.76-1.379a1 1 0 00-.076-1.822l-10-4z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Inventory</span
                >
              </a>
            </div>
            <!-- end-link-group-1 -->
            <h3 class="mt-4 text-sm font-semibold">Additional</h3>
            <!-- link-group-2 -->
            <div class="menu-2">
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-6 w-6"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50">Pos</span>
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Orders</span
                >
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10.496 2.132a1 1 0 00-.992 0l-7 4A1 1 0 003 8v7a1 1 0 100 2h14a1 1 0 100-2V8a1 1 0 00.496-1.868l-7-4zM6 9a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1zm3 1a1 1 0 012 0v3a1 1 0 11-2 0v-3zm5-1a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50">Media</span>
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Providers</span
                >
              </a>
            </div>
            <!-- end-link-group-2 -->

            <h3 class="text-sm font-semibold">Menu</h3>
            <!-- link-group-1 -->
            <div class="menu-1">
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10.496 2.132a1 1 0 00-.992 0l-7 4A1 1 0 003 8v7a1 1 0 100 2h14a1 1 0 100-2V8a1 1 0 00.496-1.868l-7-4zM6 9a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1zm3 1a1 1 0 012 0v3a1 1 0 11-2 0v-3zm5-1a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Inventory</span
                >
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M2 5a2 2 0 012-2h12a2 2 0 012 2v10a2 2 0 01-2 2H4a2 2 0 01-2-2V5zm3.293 1.293a1 1 0 011.414 0l3 3a1 1 0 010 1.414l-3 3a1 1 0 01-1.414-1.414L7.586 10 5.293 7.707a1 1 0 010-1.414zM11 12a1 1 0 100 2h3a1 1 0 100-2h-3z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Inventory</span
                >
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 1.944A11.954 11.954 0 012.166 5C2.056 5.649 2 6.319 2 7c0 5.225 3.34 9.67 8 11.317C14.66 16.67 18 12.225 18 7c0-.682-.057-1.35-.166-2.001A11.954 11.954 0 0110 1.944zM11 14a1 1 0 11-2 0 1 1 0 012 0zm0-7a1 1 0 10-2 0v3a1 1 0 102 0V7z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Inventory</span
                >
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M6.672 1.911a1 1 0 10-1.932.518l.259.966a1 1 0 001.932-.518l-.26-.966zM2.429 4.74a1 1 0 10-.517 1.932l.966.259a1 1 0 00.517-1.932l-.966-.26zm8.814-.569a1 1 0 00-1.415-1.414l-.707.707a1 1 0 101.415 1.415l.707-.708zm-7.071 7.072l.707-.707A1 1 0 003.465 9.12l-.708.707a1 1 0 001.415 1.415zm3.2-5.171a1 1 0 00-1.3 1.3l4 10a1 1 0 001.823.075l1.38-2.759 3.018 3.02a1 1 0 001.414-1.415l-3.019-3.02 2.76-1.379a1 1 0 00-.076-1.822l-10-4z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Inventory</span
                >
              </a>
            </div>
            <!-- end-link-group-1 -->
            <h3 class="mt-4 text-sm font-semibold">Additional</h3>
            <!-- link-group-2 -->
            <div class="menu-2">
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-6 w-6"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50">Pos</span>
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Orders</span
                >
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10.496 2.132a1 1 0 00-.992 0l-7 4A1 1 0 003 8v7a1 1 0 100 2h14a1 1 0 100-2V8a1 1 0 00.496-1.868l-7-4zM6 9a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1zm3 1a1 1 0 012 0v3a1 1 0 11-2 0v-3zm5-1a1 1 0 00-1 1v3a1 1 0 102 0v-3a1 1 0 00-1-1z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50">Media</span>
              </a>
              <a class="mt-2 flex items-center" href="">
                <span>
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </span>
                <span class="ml-2 text-gray-200 hover:text-gray-50"
                  >Providers</span
                >
              </a>
            </div>
            <!-- end-link-group-2 -->
          </div>
        </div>
      </div>
    </aside>
    <!-- end-sidebar -->
    <!-- main-container -->
    <div class="flex flex-col flex-1 h-ful">
      <!-- top-menu -->
      <header class="relative z-10 bg-white flex-shrink-0 border-b shadow">
        <div class="flex items-center justify-between p-2">
          <!-- alt-site-title and menu-toggle-icon -->
          <div class="flex items-center">
            <span
              class="
                p-2
                font-semibold
                text-2xl text-gray-500
                tracking-wide
                uppercase
                lg:hidden
              "
              >ABC</span
            >
            <span>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5 text-gray-500"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                  clip-rule="evenodd"
                />
              </svg>
            </span>
          </div>
          <!-- end-alt-site-title and menu-toggle-icon -->

          <!-- search icon -->
          <div
            class="
              items-center
              hidden
              px-2
              space-x-2
              md:flex-1 md:flex md:mr-auto md:ml-5
            "
          >
            <label for="search">
              <svg
                class="w-5 h-5 text-gray-500"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
                ></path>
              </svg>
            </label>
            <input
              id="search"
              type="text"
              placeholder="Search"
              class="
                px-4
                py-3
                rounded-md
                border-none
                hover:bg-gray-100
                lg:max-w-sm
                md:py-2 md:flex-1
                focus:outline-none
                md:focus:bg-gray-100 md:focus:shadow md:focus:ring-1
              "
            />
          </div>
          <!-- end search icon -->
          <!-- right-menu -->
          <div class="relative flex items-center space-x-3">
            <!-- Search button -->
            <button
              class="
                p-2
                bg-gray-100
                rounded-full
                md:hidden
                focus:outline-none focus:ring
                hover:bg-gray-200
              "
            >
              <svg
                class="w-6 h-6 text-gray-500"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
                ></path>
              </svg>
            </button>

            <div class="items-center hidden space-x-3 md:flex">
              <!-- Notification Button -->
              <div class="relative">
                <!-- red dot -->
                <div
                  class="
                    absolute
                    right-0
                    p-1
                    bg-red-400
                    rounded-full
                    animate-ping
                  "
                ></div>
                <div
                  class="absolute right-0 p-1 bg-red-400 border rounded-full"
                ></div>
                <button
                  id="notification"
                  class="
                    notification
                    p-2
                    bg-gray-100
                    rounded-full
                    hover:bg-gray-200
                    focus:outline-none focus:ring
                  "
                >
                  <svg
                    class="w-6 h-6 text-gray-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
                    ></path>
                  </svg>
                </button>

                <!-- Dropdown card -->
                <div
                  id="notification-body"
                  class="
                    notification-body
                    absolute
                    w-48
                    max-w-md
                    mt-3
                    transform
                    bg-white
                    rounded-md
                    shadow-lg
                    -translate-x-3/4
                    min-w-max
                    hidden
                  "
                >
                  <div class="p-4 font-medium border-b">
                    <span class="text-gray-800">Notification</span>
                  </div>
                  <ul class="flex flex-col p-2 my-2 space-y-1">
                    <li>
                      <a
                        href="#"
                        class="
                          block
                          px-2
                          py-1
                          transition
                          rounded-md
                          hover:bg-gray-100
                        "
                        >Link</a
                      >
                    </li>
                    <li>
                      <a
                        href="#"
                        class="
                          block
                          px-2
                          py-1
                          transition
                          rounded-md
                          hover:bg-gray-100
                        "
                        >Another Link</a
                      >
                    </li>
                  </ul>
                  <div
                    class="
                      flex
                      items-center
                      justify-center
                      p-4
                      text-blue-700
                      underline
                      border-t
                    "
                  >
                    <a href="#">See All</a>
                  </div>
                </div>
              </div>

              <!-- Services Button -->
              <div>
                <button
                  class="
                    p-2
                    bg-gray-100
                    rounded-full
                    hover:bg-gray-200
                    focus:outline-none focus:ring
                  "
                >
                  <svg
                    class="w-6 h-6 text-gray-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"
                    ></path>
                  </svg>
                </button>

                <!-- Dropdown -->
                <div
                  class="
                    absolute
                    mt-3
                    transform
                    bg-white
                    rounded-md
                    shadow-lg
                    -translate-x-3/4
                    min-w-max
                  "
                  style="display: none"
                >
                  <div class="p-4 text-lg font-medium border-b">
                    Web apps &amp; services
                  </div>
                  <ul class="flex flex-col p-2 my-3 space-y-3">
                    <li>
                      <a
                        href="#"
                        class="
                          flex
                          items-start
                          px-2
                          py-1
                          space-x-2
                          rounded-md
                          hover:bg-gray-100
                        "
                      >
                        <span class="block mt-1">
                          <svg
                            class="w-6 h-6 text-gray-500"
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke="currentColor"
                          >
                            <path
                              fill="#fff"
                              d="M12 14l9-5-9-5-9 5 9 5z"
                            ></path>
                            <path
                              fill="#fff"
                              d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"
                            ></path>
                            <path
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              stroke-width="2"
                              d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222"
                            ></path>
                          </svg>
                        </span>
                        <span class="flex flex-col">
                          <span class="text-lg">Atlassian</span>
                          <span class="text-sm text-gray-400"
                            >Lorem ipsum dolor sit.</span
                          >
                        </span>
                      </a>
                    </li>
                    <li>
                      <a
                        href="#"
                        class="
                          flex
                          items-start
                          px-2
                          py-1
                          space-x-2
                          rounded-md
                          hover:bg-gray-100
                        "
                      >
                        <span class="block mt-1">
                          <svg
                            class="w-6 h-6 text-gray-500"
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke="currentColor"
                          >
                            <path
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              stroke-width="2"
                              d="M16 12a4 4 0 10-8 0 4 4 0 008 0zm0 0v1.5a2.5 2.5 0 005 0V12a9 9 0 10-9 9m4.5-1.206a8.959 8.959 0 01-4.5 1.207"
                            ></path>
                          </svg>
                        </span>
                        <span class="flex flex-col">
                          <span class="text-lg">Slack</span>
                          <span class="text-sm text-gray-400"
                            >Lorem ipsum, dolor sit amet consectetur adipisicing
                            elit.</span
                          >
                        </span>
                      </a>
                    </li>
                  </ul>
                  <div
                    class="
                      flex
                      items-center
                      justify-center
                      p-4
                      text-blue-700
                      underline
                      border-t
                    "
                  >
                    <a href="#">Show all apps</a>
                  </div>
                </div>
              </div>

              <!-- Options Button -->
              <div class="relative">
                <button
                  class="
                    p-2
                    bg-gray-100
                    rounded-full
                    hover:bg-gray-200
                    focus:outline-none focus:ring
                  "
                >
                  <svg
                    class="w-6 h-6 text-gray-500"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"
                    ></path>
                  </svg>
                </button>

                <!-- Dropdown card -->
                <div
                  class="
                    absolute
                    w-40
                    max-w-sm
                    mt-3
                    transform
                    bg-white
                    rounded-md
                    shadow-lg
                    -translate-x-3/4
                    min-w-max
                  "
                  style="display: none"
                >
                  <div class="p-4 font-medium border-b">
                    <span class="text-gray-800">Options</span>
                  </div>
                  <ul class="flex flex-col p-2 my-2 space-y-1">
                    <li>
                      <a
                        href="#"
                        class="
                          block
                          px-2
                          py-1
                          transition
                          rounded-md
                          hover:bg-gray-100
                        "
                        >Link</a
                      >
                    </li>
                    <li>
                      <a
                        href="#"
                        class="
                          block
                          px-2
                          py-1
                          transition
                          rounded-md
                          hover:bg-gray-100
                        "
                        >Another Link</a
                      >
                    </li>
                  </ul>
                  <div
                    class="
                      flex
                      items-center
                      justify-center
                      p-4
                      text-blue-700
                      underline
                      border-t
                    "
                  >
                    <a href="#">See All</a>
                  </div>
                </div>
                <!-- end Dropdown card -->
              </div>
              <!-- end-option-button -->
            </div>

            <!-- avatar button -->
            <div class="relative">
              <button
                class="
                  p-1
                  bg-gray-200
                  rounded-full
                  focus:outline-none focus:ring
                "
              >
                <img
                  class="object-cover w-8 h-8 rounded-full"
                  src="https://avatars0.githubusercontent.com/u/57622665?s=460&amp;u=8f581f4c4acd4c18c33a87b3e6476112325e8b38&amp;v=4"
                  alt="Ahmed Kamel"
                />
              </button>
              <!-- green dot -->
              <div
                class="
                  absolute
                  right-0
                  p-1
                  bg-green-400
                  rounded-full
                  bottom-3
                  animate-ping
                "
              ></div>
              <div
                class="
                  absolute
                  right-0
                  p-1
                  bg-green-400
                  border border-white
                  rounded-full
                  bottom-3
                "
              ></div>

              <!-- Dropdown card -->
              <div
                class="
                  absolute
                  mt-3
                  transform
                  -translate-x-full
                  bg-white
                  rounded-md
                  shadow-lg
                  min-w-max
                  hidden
                "
              >
                <div class="flex flex-col p-4 space-y-1 font-medium border-b">
                  <span class="text-gray-800">Ahmed Kamel</span>
                  <span class="text-sm text-gray-400"
                    >ahmed.kamel@example.com</span
                  >
                </div>
                <ul class="flex flex-col p-2 my-2 space-y-1">
                  <li>
                    <a
                      href="#"
                      class="
                        block
                        px-2
                        py-1
                        transition
                        rounded-md
                        hover:bg-gray-100
                      "
                      >Link</a
                    >
                  </li>
                  <li>
                    <a
                      href="#"
                      class="
                        block
                        px-2
                        py-1
                        transition
                        rounded-md
                        hover:bg-gray-100
                      "
                      >Another Link</a
                    >
                  </li>
                </ul>
                <div
                  class="
                    flex
                    items-center
                    justify-center
                    p-4
                    text-blue-700
                    underline
                    border-t
                  "
                >
                  <a href="#">Logout</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </header>
      <!-- end-top-menu -->
      <main class="fixed top-[55px] inset-y-0 overflow-auto px-4 py-4 flex-1">
        <slot />
      </main>
    </div>
    <!-- end-main-container -->
  </div>
</template>
