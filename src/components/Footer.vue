<script lang="ts" setup></script>

<template>
  <footer
    class="bg-slate-900 px-10 lg:px-20 py-20 text-slate-200 grid grid-cols-2 md:grid-cols-6 gap-y-10"
  >
    <div class="flex flex-col gap-2">
      <p class="uppercase font-bold">Solutions</p>

      <p class="text-sm">Marketing</p>
      <p class="text-sm">Analytics</p>
      <p class="text-sm">Data</p>
      <p class="text-sm">Cloud</p>
    </div>

    <div class="flex flex-col gap-2">
      <p class="uppercase font-bold">Support</p>

      <p class="text-sm">Pricing</p>
      <p class="text-sm">Documentation</p>
      <p class="text-sm">Guides</p>
      <p class="text-sm">Api Status</p>
    </div>

    <div class="flex flex-col gap-2">
      <p class="uppercase font-bold">Company</p>

      <p class="text-sm">About</p>
      <p class="text-sm">Legal</p>
      <p class="text-sm">Jobs</p>
      <p class="text-sm">Clients</p>
    </div>

    <div class="flex flex-col gap-2">
      <p class="uppercase font-bold">Legal</p>

      <p class="text-sm">Terms</p>
      <p class="text-sm">Privacy</p>
      <p class="text-sm">Claims</p>
      <p class="text-sm">Conditions</p>
    </div>

    <div class="col-span-2 flex flex-col gap-5">
      <p class="uppercase font-bold">SUBSCRIBE TO OUR NEWSLETTER</p>

      <p class="text-sm">
        The latest news, articles and resources, weekly in your inbox.
      </p>
      <div class="grid lg:grid-cols-4 gap-3 grid-cols-1">
        <input
          type="text"
          placeholder="Enter email"
          class="lg:col-span-3 py-2 px-3 outline-none rounded-xl text-black shadow-xl"
        />
        <button
          class="bg-orange-300 rounded-xl shadow-xl font-semibold text-black hover:bg-orange-400 duration-200 py-2"
        >
          Suscribe
        </button>
      </div>
    </div>

    <div
      class="border-slate-800 border-t-2 col-span-2 md:col-span-6 pt-8 flex items-center justify-between flex-col gap-y-10 md:flex-row"
    >
      <p class="text-orange-400 font-semibold text-lg">
        Created by Omar Mendoza
      </p>

      <div class="flex gap-5">
        <div class="h-7 w-7 bg-orange-400 rounded-full text-transparent">.</div>
        <div class="h-7 w-7 bg-orange-400 rounded-full text-transparent">.</div>
        <div class="h-7 w-7 bg-orange-400 rounded-full text-transparent">.</div>
      </div>
    </div>
  </footer>
</template>
