<script setup lang="ts">
import { StarIcon } from "@heroicons/vue/24/outline";
</script>

<template>
  <div class="px-10 lg:px-20 py-32 flex flex-col gap-5">
    <h3 class="text-center font-bold text-4xl">
      Benefits when working with us!
    </h3>
    <p class="text-center text-xl max-w-3xl mx-auto">
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eveniet suscipit
      minus sint veniam, quasi ex natus, provident repudiandae, harum tenetur
      blanditiis ullam quisquam explicabo accusantium adipisci fuga nam! Eos,
      veritatis!
    </p>

    <div
      class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 mt-24 gap-y-10 gap-x-10"
    >
      <div class="flex flex-col gap-3">
        <div class="pb-1 bg-gradient-to-r from-orange-400 to-violet-400">
          <div class="flex items-center gap-2 bg-white pb-2">
            <StarIcon class="h-6 w-6 text-orange-600" />
            <h4 class="font-semibold text-xl text-orange-600">
              Newest technology
            </h4>
          </div>
        </div>

        <p class="">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Possimus
          placeat iure magnam. Ad nihil amet et illum doloribus, possimus magni!
        </p>
      </div>

      <div class="flex flex-col gap-3">
        <div class="pb-1 bg-gradient-to-r from-orange-400 to-violet-400">
          <div class="flex items-center gap-2 bg-white pb-2">
            <StarIcon class="h-6 w-6 text-orange-600" />
            <h4 class="font-semibold text-xl text-orange-600">
              Qualified supporters
            </h4>
          </div>
        </div>

        <p class="">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Possimus
          omnis vel error hic soluta modi optio! Ipsum similique maiores earum
          deserunt.
        </p>
      </div>

      <div class="flex flex-col gap-3">
        <div class="pb-1 bg-gradient-to-r from-orange-400 to-violet-400">
          <div class="flex items-center gap-2 bg-white pb-2">
            <StarIcon class="h-6 w-6 text-orange-600" />
            <h4 class="font-semibold text-xl text-orange-600">
              Transparent service
            </h4>
          </div>
        </div>

        <p class="">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique
          minima labore error, voluptatem temporibus perferendis velit! Corporis
          tempora veritatis laudantium!
        </p>
      </div>

      <div class="flex flex-col gap-3">
        <div class="pb-1 bg-gradient-to-r from-orange-400 to-violet-400">
          <div class="flex items-center gap-2 bg-white pb-2">
            <StarIcon class="h-6 w-6 text-orange-600" />
            <h4 class="font-semibold text-xl text-orange-600">
              Greatest references
            </h4>
          </div>
        </div>

        <p class="">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim nemo
          amet cum numquam fugiat veritatis harum similique nam ipsa eligendi.
        </p>
      </div>
    </div>
  </div>
</template>
