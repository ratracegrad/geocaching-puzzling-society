<template>
  <UContainer class="py-12">
    <UPageHeader
      title="GGPS Favorite Puzzles!"
      description="A collection of our favorite geocaching puzzles recommended by the GGPS community"
    />

    <div class="mt-8">
      <UCard>
        <template #header>
          <h2 class="text-2xl font-bold">
            Featured Puzzles
          </h2>
        </template>

        <p class="text-muted">
          This section will feature our favorite geocaching puzzles. Check back soon for recommendations from the GGPS community!
        </p>

        <div class="mt-6 space-y-4">
          <UAlert
            icon="i-lucide-info"
            color="blue"
            variant="soft"
            title="Coming Soon"
            description="We're curating a list of our favorite puzzles. This section will be updated with puzzle recommendations, difficulty ratings, and helpful solving tips."
          />
        </div>
      </UCard>
    </div>
  </UContainer>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'GGPS Favorite Puzzles - Georgia Geocaching Puzzling Society',
  description: 'Browse our collection of favorite geocaching puzzles recommended by the GGPS community'
})
</script>
