<template>
  <div class="px-10 lg:px-20 py-32 flex flex-col gap-10 bg-slate-800">
    <h3 class="text-white font-bold text-4xl text-center">
      Here are our alternatives for your budget.
    </h3>
    <p class="text-center text-white max-w-3xl mx-auto text-xl">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos minus
      quisquam dolorum, quaerat omnis, dolores natus quas excepturi animi
      tenetur consequuntur asperiores ipsam praesentium aperiam ea eos dolor
      assumenda eius.
    </p>

    <div
      class="grid md:grid-cols-2 lg:grid-cols-3 items-center mt-10 gap-y-10 gap-x-20"
    >
      <Plan :price="49" :checked="3" :name="'standard'" />
      <Plan :price="79" :checked="5" :name="'pro'" />
      <Plan :price="99" :checked="7" :name="'enterprise'" />
    </div>
  </div>
</template>

<script setup lang="ts">
import Plan from "@/components/Plan.vue";
</script>

<style scoped></style>
