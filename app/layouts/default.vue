<template>
  <div>
    <UBanner
      color="neutral"
      class="py-8 px-4"
    >
      <template #title>
        <div class="flex items-center gap-3">
          <NuxtImg src="/cropped-Logo-Smaller.webp" />
          <span class="text-2xl font-bold text-red-500">Welcome to the Georgia Geocaching Puzzling Society</span>
        </div>
      </template>
    </UBanner>
    <AppHeader />

    <UMain>
      <slot />
    </UMain>
  </div>
</template>
