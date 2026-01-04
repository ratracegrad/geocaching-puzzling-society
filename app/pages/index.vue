<template>
  <div>
    <UPageHero
      title="Welcome to the Georgia Geocaching Puzzling Society (GGPS)!"
    />

    <UContainer class="py-12">
      <p class="mb-4">
        Welcome to the home of the GGPS!
      </p>

      <p class="mb-4">
        We're glad you're here! We have some great information on the site for you. Please use the menu at the top of the page to navigate between sections.
      </p>

      <p class="mb-4">
        Our next GGPS event will be held on Saturday, July 30th, from 10:00 AM to 12:30 PM! It will be held in Nicholson, Georgia and be at the Nicholson Public Library. This session will be a “review” session and we will have an activity-based event where you will have an opportunity to practice the different puzzle-solving techniques we have covered the first half of the year!
      </p>

      <p class="mb-4">
        The GC code for that event will be available soon. Once published, you can click the link in the menu to go straight to the event page! If you plan on attending, please log a “Will Attend” so we know you'll be there!
      </p>

      <NuxtImg
        src="/resources.webp"
        alt="GGPS"
        class="block mx-auto"
        width="295"
        height="300"
      />
    </UContainer>
  </div>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Home - Georgia Geocaching Puzzling Society',
  description: 'Welcome to the home of the Georgia Geocaching Puzzling Society (GGPS)'
})
</script>
