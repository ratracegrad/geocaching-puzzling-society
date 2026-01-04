<template>
  <UContainer class="py-12">
    <UPageHeader
      title="Publishing Contests!"
      :ui="{ title: 'text-red-500' }"
    />

    <UPageGrid class="mt-8 grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-8">
      <div>
        <h2 class="text-2xl mb-4 font-bold text-red-500">
          General
        </h2>
        <p class="text-muted mb-4">
          One of the goals of the GGPS is to Encourage new puzzles to be hidden! To that end, the GGPS will sponsor a Puzzle Hiding contest each month!
        </p>
        <p class="text-muted mb-4">
          You will find the rules posted here, as well as on our Facebook page. They will change from month to month.
        </p>
        <p class="text-muted mb-4">
          Each person that submits a ticket for a drawing at the next month’s event. We will give away a cool hider pack that includes a couple of containers and some other goodies.
        </p>
        <p class="text-muted mb-4">
          Each month, the GGPS team will review the submissions and pick some as our “Favorite”. The “Favorites” will receive an additional FIVE entries in the drawing, PLUS be added to your list of GGPS Favorite Caches, PLUS receive a cool graphic they can display on their cache page to show that they received the honor!!
        </p>
        <h2 class="text-2xl mb-4 mt-8 font-bold text-red-500">
          November Assignment
        </h2>
        <p class="text-muted mb-4">
          This is your puzzle hide assignment for November!
        </p>
        <p class="text-muted mb-4">
          Create a puzzle using the lessons we covered in the October Event (<ULink
            to="https://drive.google.com/file/d/1ARqR9ukrTjA27XTEa6RDu4L1MBNHEh0O/view?usp=sharing"
            external
            target="_blank"
            class="text-sm text-primary"
          >Things You Can Find on a Cache Page!</ULink>)! You can use just one method, or a combination of methods in the puzzle.
        </p>
        <p class="text-muted mb-4">
          Here are the rules for the hide:
        </p>
        <ul class="list-disc list-inside text-muted mb-4">
          <li>Puzzle must be in Georgia.</li>
          <li>Puzzle must feature one or more of the concepts we covered in the September GGPS event.</li>
          <li>Puzzle must be mostly solvable from home.</li>
          <li>Puzzle must be rated no more than a 4.0D.</li>
          <li>Send your name, Geo-nick, and the GC code of your puzzle to ThePuzzlePosse@gmail.com no later than Monday, 11/28/22. We will pick our favorites and announce them at the December event!</li>
        </ul>
        <p class="text-muted mb-4">
          Send your name, Geo-nick, and the GC code of your puzzle to <ULink
            to="mailto:ThePuzzlePosse@gmail.com"
            class="text-sm text-primary"
          >ThePuzzlePosse@gmail.com</ULink> no later than Monday, 11/28/22. We will pick our favorites and announce them at the December event!
        </p>
      </div>

      <NuxtImg
        src="/publishing-contests.webp"
        alt="Publishing Contests"
        class="w-full h-auto"
      />
    </UPageGrid>
  </UContainer>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Publishing Contests - Georgia Geocaching Puzzling Society',
  description: 'Information about GGPS puzzle publishing contests and competitions'
})
</script>
