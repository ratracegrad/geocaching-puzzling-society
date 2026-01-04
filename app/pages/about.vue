<template>
  <UContainer class="py-12">
    <UPageHeader
      title="About the GGPS"
      :ui="{ title: 'text-red-500' }"
    />

    <UPageGrid class="mt-8 grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-8">
      <NuxtImg
        src="/resources.webp"
        alt="Resources"
        width="295"
        height="300"
      />

      <div class="mt-8 space-y-6">
        <h2 class="text-2xl mb-4 font-bold text-red-500">
          Our Goals
        </h2>

        <p>The GGPS has three main goals. We often refer to them as “The Three E’s”! Here they are:</p>

        <p><b>Educate:</b> teach important skills and help geocachers find important resources to help them solve puzzles.</p>

        <p><b>Encourage:</b> Encourage people to look at puzzles and develop a love of puzzling and hide more puzzle caches!</p>

        <p><b>Engage:</b> We want to engage and create a community that supports creating and solving puzzles in Georgia!</p>

        <USeparator
          size="lg"
          color="neutral"
        />

        <h2 class="text-2xl mb-4 font-bold text-red-500">
          How We Came to Be
        </h2>

        <p>In 2020, the COVID-19 pandemic hit. When that happened, caching became limited, so a small group decided it was a great time to try to sharpen our puzzle skills! So, one day in April Bragger407, GeoMonkeyTiger!, LaFavorite Cacher, and poeanne met via Zoom. It was a great group in that each team member brought a different skillset to the table!</p>

        <p>It was decided early on that the goal was to actually solve the puzzles– not just share coordinates. We started easy, by solving all the 1.0 Difficulty puzzles in the state! We moved on to 1.5D, and then made a list of every puzzle cache within 30 miles of each our homes to solve!</p>

        <p>Somewhere along the line, we decided to coin ourselves “The Puzzle Posse”. The name stuck. 😋</p>

        <p>Over the course of nearly 2 years, we solved hundreds of puzzles together. We had a lot of laughs, and as the pandemic eased a bit, we found times to hunt many of the puzzles we had solved together. A great friendship evolved, and even though we had a long way to go, we all became better puzzlers!</p>

        <p>At the end of 2021, we decided we wanted to try to find a way to share what we had learned and try to build some excitement in the Geocaching community. We knew that puzzle caches can be intimidating for many, so we came up with the Georgia Geocaching Puzzling Community! We decided on a combination of events to help teach puzzling techniques, contests to promote new puzzle creation, and creating a community for people to meet new puzzlers and form their own Puzzle Posses!</p>

        <p>We were able to set up a partnership with local libraries, which would provide a perfect place to hold our events! Our first event was held on January 29th, 2022 and we had over 40 people in attendance!</p>

        <p>Each month, we continue to hold events that feature specific puzzle-solving techniques! We look forward to continuing to build the community!</p>

        <USeparator
          size="lg"
          color="neutral"
        />

        <h2 class="text-2xl mb-4 font-bold text-red-500">
          Contact Us
        </h2>
      </div>
    </UPageGrid>

    <UPageGrid class="mt-8 grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-8">
      <NuxtImg
        src="/contact-us.png"
        alt="Contact Us"
        class="w-full h-auto"
      />

      <div>
        <h2 class="text-2xl mb-4 font-bold text-red-500">
          Group Email
        </h2>
        <a
          href="mailto:ThePuzzlePosse@gmail.com"
          target="_blank"
          class="text-sm text-primary"
        >ThePuzzlePosse@gmail.com</a>

        <p class="mt-4">From Left to Right: Sue LaFave (LaFavorite Cacher), poeanne (Anne Poe), Matt Janiak (GeoMonkeyTiger!)</p>
      </div>
    </UPageGrid>
  </UContainer>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'About the GGPS - Georgia Geocaching Puzzling Society',
  description: 'Learn about the Georgia Geocaching Puzzling Society and our mission to build a puzzling community'
})
</script>
