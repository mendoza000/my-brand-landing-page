<script lang="ts" setup>
import {
  AcademicCapIcon,
  ArrowTrendingUpIcon,
  BoltIcon,
  HeartIcon,
} from "@heroicons/vue/24/outline";
</script>

<template>
  <div
    class="items-center gap-5 px-10 pt-24 pb-20 md:grid md:grid-cols-2 lg:px-24 bg-slate-50"
  >
    <div class="flex flex-col max-w-xl gap-5">
      <p class="opacity-70">
        Lorem ipsum dolor sit amet consectetur adipisicing.
      </p>
      <h2 class="text-4xl font-bold lg:text-5xl">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit
      </h2>
      <p class="text-xl">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Id ratione
        animi sed asperiores sit. Id.
      </p>
      <button
        class="max-w-sm py-3 font-semibold duration-200 bg-orange-300 shadow-xl rounded-xl hover:bg-orange-400 hover:scale-105 hover:shadow-violet-300"
      >
        See our plans
      </button>
    </div>

    <div class="">
      <img src="/header-image.svg" alt="mybrand-image" class="w-full h-full" />
    </div>

    <div
      class="flex flex-col items-center justify-center max-w-2xl col-span-2 py-5 mx-auto duration-200 bg-white shadow-xl px-7 lg:px-16 rounded-xl hover:shadow-violet-300"
    >
      <h2 class="mb-5 text-xl font-bold">Our works</h2>
      <div class="grid grid-cols-2 gap-x-10 gap-y-3 md:grid-cols-4">
        <div class="flex items-center gap-2">
          <AcademicCapIcon class="text-orange-600 w-7 h-7" />
          <p class="font-semibold">Service</p>
        </div>
        <div class="flex items-center gap-2">
          <ArrowTrendingUpIcon class="text-orange-600 w-7 h-7" />
          <p class="font-semibold">Service</p>
        </div>
        <div class="flex items-center gap-2">
          <BoltIcon class="text-orange-600 w-7 h-7" />
          <p class="font-semibold">Service</p>
        </div>
        <div class="flex items-center gap-2">
          <HeartIcon class="text-orange-600 w-7 h-7" />
          <p class="font-semibold">Service</p>
        </div>
      </div>
    </div>
  </div>
</template>
