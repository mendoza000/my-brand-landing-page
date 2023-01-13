<template>
  <div
    class="bg-white flex flex-col gap-5 py-12 px-6 rounded-xl shadow-xl lg:px-10 hover:shadow-orange-900 duration-200"
  >
    <div
      class="bg-gradient-to-tr from-orange-400 to-violet-400 rounded-xl p-1 max-w-[8rem] -mt-5"
    >
      <div class="flex max-w-[8rem] rounded-xl py-1" :class="bgPlan()">
        <span class="font-semibold uppercase text-center w-full">{{
          props.name
        }}</span>
      </div>
    </div>

    <p class="text-3xl font-bold">${{ props.price }} p/month</p>
    <p class="opacity-90">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fugit tempora
      dicta id placeat, libero ut.
    </p>

    <div class="flex flex-col gap-5">
      <div v-for="i in 7" class="flex gap-3 items-center">
        <CheckIcon v-if="i <= props.checked" class="h-7 w-7 text-green-500" />
        <XMarkIcon v-else class="h-7 w-7 text-red-500" />
        <p class="text-lg font-semibold">Lorem ipsum dolor sit.</p>
      </div>
    </div>

    <button
      class="bg-orange-300 font-semibold py-3 shadow-xl rounded-xl mt-5 hover:bg-orange-400 duration-200"
    >
      Start {{ props.name }} plan
    </button>
  </div>
</template>

<script lang="ts" setup>
import { CheckIcon, XMarkIcon } from "@heroicons/vue/24/outline";

const props = defineProps({
  name: { type: String, required: true },
  price: { type: Number, required: true },
  checked: { type: Number, required: true },
});

const bgPlan = () => {
  switch (props.name) {
    case "standard":
      return "bg-white";

    case "pro":
      return "bg-white text-orange-500";

    case "enterprise":
      return "bg-white text-violet-500";
  }
};
</script>
