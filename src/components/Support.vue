<script setup lang="ts">
import {
  ArrowRightIcon,
  CloudIcon,
  ChartBarIcon,
  ShieldCheckIcon,
} from "@heroicons/vue/24/outline";
</script>

<template>
  <div
    class="flex flex-col px-10 py-32 text-white lg:px-20 bg-slate-800 gap-y-5"
  >
    <h3 class="text-4xl font-semibold text-center">Need support?</h3>
    <p class="max-w-3xl mx-auto text-xl text-center">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo illum ullam
      incidunt a ipsam corporis excepturi. Ipsam, enim possimus omnis ut non ex
      dolore error optio eveniet accusantium, quod corporis.
    </p>

    <div
      class="flex flex-col mt-10 gap-y-15 md:grid md:grid-cols-2 justify-center items-center gap-x-10 gap-y-14 lg:grid-cols-3"
    >
      <div
        class="relative flex flex-col gap-5 px-10 py-10 bg-white shadow-xl text-slate-900 rounded-xl"
      >
        <h4 class="text-2xl font-semibold">Online data</h4>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore ea
          deleniti magni.
        </p>
        <button
          class="flex items-center justify-center gap-2 py-2 text-center duration-200 bg-orange-300 shadow-xl rounded-xl hover:bg-orange-400 mt-5"
        >
          Download now
          <ArrowRightIcon class="w-4 h-4" />
        </button>

        <div
          class="absolute p-4 text-white bg-orange-400 shadow-xl left-8 -top-8 rounded-xl"
        >
          <CloudIcon class="w-7 h-7" />
        </div>
      </div>

      <div
        class="relative flex flex-col gap-5 px-10 py-10 bg-white shadow-xl text-slate-900 rounded-xl"
      >
        <h4 class="text-2xl font-semibold">Sales</h4>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore ea
          deleniti magni.
        </p>
        <button
          class="flex items-center justify-center gap-2 py-2 text-center duration-200 bg-orange-300 shadow-xl rounded-xl hover:bg-orange-400 mt-5"
        >
          Contact us
          <ArrowRightIcon class="w-4 h-4" />
        </button>

        <div
          class="absolute p-4 text-white bg-orange-400 shadow-xl left-8 -top-8 rounded-xl"
        >
          <ChartBarIcon class="w-7 h-7" />
        </div>
      </div>

      <div
        class="relative flex flex-col gap-5 px-10 py-10 bg-white shadow-xl text-slate-900 rounded-xl md:col-span-2 lg:col-span-1"
      >
        <h4 class="text-2xl font-semibold">Security</h4>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore ea
          deleniti magni.
        </p>
        <button
          class="flex items-center justify-center gap-2 py-2 text-center duration-200 bg-orange-300 shadow-xl rounded-xl hover:bg-orange-400 mt-5"
        >
          Run a test
          <ArrowRightIcon class="w-4 h-4" />
        </button>

        <div
          class="absolute p-4 text-white bg-orange-400 shadow-xl left-8 -top-8 rounded-xl"
        >
          <ShieldCheckIcon class="w-7 h-7" />
        </div>
      </div>
    </div>
  </div>
</template>
