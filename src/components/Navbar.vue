<script lang="ts" setup>
import { Bars3Icon } from "@heroicons/vue/24/outline";
</script>

<template>
  <div
    class="fixed top-0 z-10 flex items-center justify-between min-w-full py-5 bg-white shadow-xl px-7 md:px-12"
  >
    <h1 class="text-xl font-semibold">My Brand!</h1>

    <div class="items-center gap-10 hidden lg:flex">
      <p
        class="hover:text-orange-500 font-semibold duration-200 cursor-pointer"
      >
        About
      </p>
      <p
        class="hover:text-orange-500 font-semibold duration-200 cursor-pointer"
      >
        Support
      </p>
      <p
        class="hover:text-orange-500 font-semibold duration-200 cursor-pointer"
      >
        Benefits
      </p>
      <p
        class="hover:text-orange-500 font-semibold duration-200 cursor-pointer"
      >
        Priecing
      </p>

      <button
        class="font-semibold bg-orange-300 px-5 py-2 rounded-xl shadow-xl duration-200 hover:bg-orange-400"
      >
        Get started
      </button>
    </div>

    <Bars3Icon class="w-7 h-7 lg:hidden" />
  </div>
</template>
