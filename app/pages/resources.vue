<template>
  <UContainer class="py-12">
    <UPageHeader
      title="Helpful Resources"
      :ui="{ title: 'text-red-500' }"
    />

    <UPageGrid class="mt-8 grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-8">
      <p class="text-muted mb-4">
        These are some links to sites we find useful in solving puzzles!
      </p>

      <NuxtImg
        src="/resources.webp"
        alt="Resources"
        width="295"
        height="300"
      />
    </UPageGrid>

    <div>
      <h2 class="text-2xl mb-4 font-bold">
        Our Favorites
      </h2>
      <p class="text-muted mb-4">
        These are several of the Puzzle Posse's “Go-To” links. Ones we use quite often!
      </p>
      <p class="text-muted mb-4">
        <ULink
          href="https://www.geocachingtoolbox.com/"
          target="_blank"
          class="text-sm text-primary"
        >Geocaching Toolbox</ULink>: This is a collection of several useful tools in solving puzzles. Highlights include code and cipher translations, steganography tools, antipode calculators, and more!
      </p>

      <p class="text-muted mb-4">
        <ULink
          href="https://theblob.org/rot.cgi"
          target="_blank"
          class="text-sm text-primary"
        >The Blob (ROT Converter):</ULink> A ROT converter that will check through all the ROT possibilities with one click!
      </p>

      <p class="text-muted mb-4">
        <ULink
          href="https://www.dcode.fr/en"
          target="_blank"
          class="text-sm text-primary"
        >DCODE:</ULink> A pretty advanced site with tons of different puzzle solving tools. Includes some more advanced versions of things you see on the Geocaching Toolbox
      </p>

      <p class="text-muted mb-4">
        <ULink
          href="https://www.boxentriq.com/"
          target="_blank"
          class="text-sm text-primary"
        >BoxEntriq:</ULink> Another powerful code/cipher breaking tool. Includes a tool that will try to guess as to the cipher/code used.
      </p>

      <p class="text-muted mb-4">
        <ULink
          href="https://www.earthpoint.us/Convert.aspx"
          target="_blank"
          class="text-sm text-primary"
        >Earth Point Coordinate Tools:</ULink> Often, it is necessary to convert coordinates to different formats, and we like this tool. It will accept nearly all coordinate formats and will display multiple conversions simultaneously!
      </p>

      <p class="text-muted mb-4">
        <ULink
          href="http://www.geolifeline.com/projection.php"
          target="_blank"
          class="text-sm text-primary"
        >GeoLifeLine:</ULink> A simple-to-use, coordinate projection tool
      </p>
    </div>
  </UContainer>
</template>

<script setup lang="ts">
useSeoMeta({
  title: 'Helpful Resources - Georgia Geocaching Puzzling Society',
  description: 'Tools, guides, and resources to help you solve geocaching puzzles'
})
</script>
