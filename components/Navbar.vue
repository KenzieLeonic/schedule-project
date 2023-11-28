<template>
  <div class="">
    <div class="navbar bg-base-100">
      <div class="navbar-start">
        <div class="dropdown">
          <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
            <NuxtLink to="#">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-5 h-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M4 6h16M4 12h8m-8 6h16"
                />
              </svg>
            </NuxtLink>
          </div>
          <ul
            class="menu menu-sm navbar-center dropdown-content mt-3 z-[1] shadow bg-base-100 rounded-box w-full"
          >
            <li><a>Item 1</a></li>
            <li>
              <a>Parent</a>
              <ul class="p-2">
                <li><a>Submenu 1</a></li>
                <li><a>Submenu 2</a></li>
              </ul>
            </li>
            <li><a>Item 3</a></li>
          </ul>
        </div>
        <a class="text-xl btn btn-ghost">daisyUI</a>
      </div>
      <div class="hidden navbar-center lg:flex">
        <ul class="px-1 menu menu-horizontal">
          <li><a>Item 1</a></li>
          <li>
            <details>
              <summary>Parent</summary>
              <ul class="p-2">
                <li><a>Submenu 1</a></li>
                <li><a>Submenu 2</a></li>
              </ul>
            </details>
          </li>
          <li><a>Item 3</a></li>
        </ul>
      </div>
      <div class="navbar-end">
        <NuxtLink to="auth/login">
          <botton class="inline-flex items-center justify-center px-5 py-3 mr-3 text-center btn btn-ghost"> Log in </botton>
        </NuxtLink>
        <NuxtLink to="/auth/register">
          <botton
            class="inline-flex items-center justify-center px-5 py-3 mr-3 text-center btn btn-primary"
          >
            Get started
            <svg
              class="w-5 h-5 ml-2 -mr-1"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </botton>
        </NuxtLink>
        <div class="mx-8">
          <BaseSwitchtheme />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "Navbar",
};
</script>

<style></style>
