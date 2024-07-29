<script setup lang="ts">
import Love from "@/assets/Love.vue";
import LoveRed from "@/assets/LoveRed.vue";
import Star from "@/assets/Star.vue";
</script>

<template>
  <main class="flex flex-col gap-14 px-[100px] py-10">
    <div>
      <h1
        class="text-black font-plus-jakarta-sans text-2xl font-semibold leading-[34px]"
      >
        Hotel in Jakarta, Indosnesia
      </h1>
      <p
        class="text-[#898787] font-plus-jakarta-sans text-base font-normal leading-[24px]"
      >
        We found <samp class="text-black font-bold">2478</samp> Premium Hotels
      </p>
    </div>
    <div class="flex gap-10">
      <div class="flex flex-col gap-6">
        <div class="w-[292px] h-[292px] bg-[#D9D9D9] rounded-3xl">
          <div
            class="inline-flex p-2 items-center gap-2.5 bg-[#fff] rounded-full mt-6 ml-6"
          >
            <Love />
          </div>
        </div>
        <div class="flex flex-col gap-2">
          <h1
            class="text-black font-plus-jakarta-sans text-xl font-semibold leading-[30px]"
          >
            Harmony Suites
          </h1>
          <p
            class="text-[#898787] font-plus-jakarta-sans text-sm font-normal leading-[24px]"
          >
            Blissful Street, Shouth Jakarta
          </p>
          <div class="flex items-center gap-2">
            <Star />
            <Star />
            <Star />
            <Star />
            <Star />
            <span>(4.8)</span>
          </div>
        </div>
      </div>
      <div class="flex flex-col gap-6">
        <div class="w-[292px] h-[292px] bg-[#D9D9D9] rounded-3xl">
          <div
            class="inline-flex p-2 items-center gap-2.5 bg-[#fff] rounded-full mt-6 ml-6"
          >
            <LoveRed />
          </div>
        </div>
        <div class="flex flex-col gap-2">
          <h1
            class="text-black font-plus-jakarta-sans text-xl font-semibold leading-[30px]"
          >
            Harmony Suites
          </h1>
          <p
            class="text-[#898787] font-plus-jakarta-sans text-sm font-normal leading-[24px]"
          >
            Blissful Street, Shouth Jakarta
          </p>
          <div class="flex items-center gap-2">
            <Star />
            <Star />
            <Star />
            <Star />
            <Star />
            <span>(4.8)</span>
          </div>
        </div>
      </div>
      <div class="flex flex-col gap-6">
        <div class="w-[292px] h-[292px] bg-[#D9D9D9] rounded-3xl">
          <div
            class="inline-flex p-2 items-center gap-2.5 bg-[#fff] rounded-full mt-6 ml-6"
          >
            <Love />
          </div>
        </div>
        <div class="flex flex-col gap-2">
          <h1
            class="text-black font-plus-jakarta-sans text-xl font-semibold leading-[30px]"
          >
            Harmony Suites
          </h1>
          <p
            class="text-[#898787] font-plus-jakarta-sans text-sm font-normal leading-[24px]"
          >
            Blissful Street, Shouth Jakarta
          </p>
          <div class="flex items-center gap-2">
            <Star />
            <Star />
            <Star />
            <Star />
            <Star />
            <span>(4.8)</span>
          </div>
        </div>
      </div>
      <div class="flex flex-col gap-6">
        <div class="w-[292px] h-[292px] bg-[#D9D9D9] rounded-3xl">
          <div
            class="inline-flex p-2 items-center gap-2.5 bg-[#fff] rounded-full mt-6 ml-6"
          >
            <LoveRed />
          </div>
        </div>
        <div class="flex flex-col gap-2">
          <h1
            class="text-black font-plus-jakarta-sans text-xl font-semibold leading-[30px]"
          >
            Harmony Suites
          </h1>
          <p
            class="text-[#898787] font-plus-jakarta-sans text-sm font-normal leading-[24px]"
          >
            Blissful Street, Shouth Jakarta
          </p>
          <div class="flex items-center gap-2">
            <Star />
            <Star />
            <Star />
            <Star />
            <Star />
            <span>(4.8)</span>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
