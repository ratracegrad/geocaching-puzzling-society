<template>
  <UContainer class="py-12">
    <UPageHeader
      title="GGPS Presentations"
    />

    <UPageGrid class="mt-8 grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-8">
      <p class="text-muted mb-4">
        Each month, we present a different topic for the puzzling community. You can view presentations from each event below!
      </p>

      <NuxtImg
        src="/presentations.webp"
        alt="Presentations"
        class="w-full h-auto"
      />
    </UPageGrid>

    <UTable
      :data="data"
      :columns="columns"
      class="mt-12"
      @select="onSelect"
    />
  </UContainer>
</template>

<script setup lang="ts">
import type { TableColumn, TableRow } from '@nuxt/ui'

useSeoMeta({
  title: 'GGPS Presentations - Georgia Geocaching Puzzling Society',
  description: 'Access presentation materials and resources from GGPS events and workshops'
})

const data = [
  {
    presentation: 'GGPS-08 October Event: Things You Can Find on a Cache Page!',
    date: 'October 29, 2022',
    link: 'https://drive.google.com/file/d/1ARqR9ukrTjA27XTEa6RDu4L1MBNHEh0O/view?usp=sharing'
  },
  {
    presentation: 'GGPS-07 September Event Let’s Get Physical!',
    date: 'September 24, 2022',
    link: 'https://drive.google.com/file/d/1OscUsFiSu74fuznHCVgmab5vEOxjj2GT/view?usp=sharing'
  },
  {
    presentation: 'GGPS-05 June Event: Using Maps to Solve Puzzles',
    date: 'June 25, 2022',
    link: 'https://drive.google.com/file/d/10AKwqgQAVJeqKQow8gHU7onUkzep3EiB/view?usp=sharing'
  },
  {
    presentation: 'GGPS-04 April Event: Using Images to Solve Puzzles!',
    date: 'April 30, 2022',
    link: 'https://drive.google.com/file/d/1l8whTYj_0us70DJa0ohJJjTgvMr52nx_/view?usp=sharing'
  },
  {
    presentation: 'GGPS-03 Solving Puzzles With Ciphers (Presented by The Waysiders!)',
    date: 'March 26, 2022',
    link: 'https://drive.google.com/file/d/152X8jSL0x3Zf-PFvQUtqhtTUyiZmgQ7b/view?usp=sharing'
  },
  {
    presentation: 'GGPS-02 February Event: Basic Codes',
    date: 'February 26, 2022',
    link: 'https://drive.google.com/file/d/1y0X1Kum119Sx42MIIp-SsOY5lH8E6ET3/view?usp=sharing'
  },
  {
    presentation: 'GGPS-01 Inaugural January Event-Intro to Puzzling!',
    date: 'January 22, 2022',
    link: 'https://drive.google.com/file/d/11MkVsn-Bs0h86fqRF4_xPKYvV1FOFo0p/view?usp=sharing'
  }
]

type TableData = {
  presentation: string
  date: string
  link: string
}

const columns: TableColumn<TableData>[] = [
  {
    accessorKey: 'presentation',
    header: 'Presentation',
    cell: ({ row }) => {
      return h('span', {
        class: 'text-primary'
      }, row.original.presentation)
    }
  },
  {
    accessorKey: 'date',
    header: 'Event Date'
  }
]

async function onSelect(e: Event, row: TableRow<TableData>) {
  await navigateTo(row.original.link, {
    open: {
      target: '_blank'
    }
  })
}
</script>
