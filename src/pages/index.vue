<script setup>
</script>

<template>
  <div class="mx-auto mt-4 max-w-3xl p-6">
    <div class="flex items-center justify-between">
      <h1 class="font-bold text-[35px] mb-2">
        Lukreate
      </h1>
      <TemColorChange />
    </div>

    <p class="font-light text-[24px] text-gray-500">
      We are a team of developers who are passionate about creating awesome products.
    </p>

    <h2 class="uppercase text-xl font-bold mt-4">
      Interested hire us?
    </h2>

    <div class="border-t border-gray-300/[.50] h-[1px] my-16 lg:my-[80px]" />

    <h2 class="font-bebas text-[27px] text-sky-700 tracking-wide mb-3">
      Projects
    </h2>

    <p class="text-[19px] text-gray-600 leading-relaxed mb-10">
      We are currently working on a few projects. We will be releasing them soon.
    </p>

    <div class="mt-8 grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-2">
      <a
        class="block rounded-xl border border-gray-200 p-8  transition hover:border-blue-500"
        href="https://driftsms.com"
      >
        <div class="flex flex-col items-center">
          <img class="h-32 w-32" src="https://lukreate.sgp1.digitaloceanspaces.com/images/drift-logo.png">

          <h2 class="mt-4 text-xl font-bold text-gray-900">Drift SMS</h2>

          <p class="mt-1 text-sm text-gray-600 text-center">
            Hassle Free Bulk SMS and Campaign Management Tool.
          </p>
        </div>

      </a>

      <a
        class="block rounded-xl border border-gray-200 p-8  transition hover:border-blue-500"
        href="https://driftsms.com"
      >
        <div class="flex flex-col items-center">
          <img class="h-32 w-32" src="https://lukreate.sgp1.digitaloceanspaces.com/images/write_mv-New.svg">

          <h2 class="mt-4 text-xl font-bold text-gray-900">Write.mv</h2>

          <p class="mt-1 text-sm text-gray-600 text-center">
            Write mv is an open source platform to write,share and spread your words online.
          </p>
        </div>

      </a>

      <a
        class="block rounded-xl border border-gray-200 p-8  transition hover:border-blue-500"
        href="https://driftsms.com"
      >
        <div class="flex flex-col items-center">
          <img class="h-32 w-32" src="https://lukreate.sgp1.digitaloceanspaces.com/images/vocalize.png">

          <h2 class="mt-4 text-xl font-bold text-gray-900">Vocalize</h2>

          <p class="mt-1 text-sm text-gray-600 text-center">
            Produce clear, natural sounding speech from your
            dhivehi content for digital broadcasting
            using text-to-speech technology.
          </p>
        </div>

      </a>
    </div>
  </div>
</template>
