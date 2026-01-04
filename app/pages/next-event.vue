<template>
  <UContainer class="py-12">
    <UPageHeader
      title="Next Event / GGPS Favorites"
      description="Information about upcoming GGPS events and our favorite puzzles"
    />

    <div class="mt-8 space-y-8">
      <UCard>
        <template #header>
          <h2 class="text-2xl font-bold">
            Upcoming Event
          </h2>
        </template>

        <div class="space-y-4">
          <div>
            <h3 class="text-lg font-semibold mb-2">
              GGPS-09 Event: MOAP (the Mother of all Puzzles)!
            </h3>
            <p class="text-muted">
              The GC code for this event will be available soon. Once published, you can access the event page directly.
            </p>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mt-6">
            <div>
              <p class="text-sm text-muted">
                Date
              </p>
              <p class="font-semibold">
                Saturday, July 30th
              </p>
            </div>
            <div>
              <p class="text-sm text-muted">
                Time
              </p>
              <p class="font-semibold">
                10:00 AM to 12:30 PM
              </p>
            </div>
            <div>
              <p class="text-sm text-muted">
                Location
              </p>
              <p class="font-semibold">
                Nicholson Public Library
              </p>
            </div>
            <div>
              <p class="text-sm text-muted">
                City
              </p>
              <p class="font-semibold">
                Nicholson, Georgia
              </p>
            </div>
          </div>

          <div class="mt-6">
            <p>
              This session will be a "review" session and we will have an activity-based event where you will have an opportunity to practice the different puzzle-solving techniques we have covered the first half of the year!
            </p>
            <p class="mt-4">
              If you plan on attending, please log a "Will Attend" so we know you'll be there!
            </p>
          </div>
        </div>
      </UCard>

      <UCard>
        <template #header>
          <h2 class="text-2xl font-bold">
            GGPS Favorites
          </h2>
        </template>

        <p class="text-muted">
          Check out our favorite puzzles! This section will be updated with links to our most recommended geocaching puzzles.
        </p>
      </UCard>
    </div>
  </UContainer>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Next Event / GGPS Favorites - Georgia Geocaching Puzzling Society',
  description: 'Information about upcoming GGPS events and our favorite geocaching puzzles'
})
</script>
