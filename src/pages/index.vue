<script setup>
</script>

<template>
  <div class="mx-auto mt-4 max-w-3xl p-6">
    <div class="flex items-center justify-between">
      <h1 class="font-bold text-[30px] mb-2">
        Lukreate
      </h1>
      <TemColorChange />
    </div>

    <p class="font-light text-[24px] text-gray-500">
      We are a team of developers who are passionate about creating awesome products.
    </p>

    <div class="border-t border-gray-300/[.50] h-[1px] my-16 lg:my-[80px]" />

    <h2 class="font-bebas text-[27px] text-sky-700 tracking-wide mb-3">
      Projects
    </h2>

    <p class="text-[19px] text-gray-600 leading-relaxed mb-10">
      We are currently working on a few projects. We will be releasing them soon.
    </p>

    <div class="grid grid-cols-1 gap-4">
      <!-- Pionear -->
      <div onclick="window.open('https://driftsms.com')" class="border border-transparent hover:border-yellow-600/[.50] flex items-start md:items-center rounded-lg cursor-pointer transition duration-300 px-8 py-4">
        <!-- Logo -->
        <div class="flex justify-center items-center w-[150px] h-[150px] -mt-1 md:mt-0">
          <img src="/drift-logo.png">
        </div>

        <!-- Details -->
        <div class="ml-6 md:ml-8">
          <h3 class="font-signika font-semibold text-[21px]">
            Drift SMS
          </h3>

          <!-- Description -->
          <p class="text-[17px] text-gray-600 leading-relaxed mb-0">
            Hassle Free Bulk SMS and Campaign Management Tool.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
