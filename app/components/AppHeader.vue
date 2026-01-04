<template>
  <UHeader title="GGPS">
    <UNavigationMenu :items="menuItems" />
  </UHeader>

</template>

<script setup lang="ts">
import type { NavigationMenuItem } from '@nuxt/ui'

const menuItems: NavigationMenuItem[] = [
  {
    label: 'Next Event/GGPS Favorites',
    to: '/next-event',
    children: [
      {
        label: 'GCA1NHM – GGPS-09 Event: MOAP (the Mother of all Puzzles)!',
        to: 'https://coord.info/GCA1NHM',
        target: '_blank'
      },
      {
        label: 'GGPS Favorite Puzzles!',
        to: 'https://coord.info/BMARCBJ',
        target: '_blank'
      },
    ]
  },
  {
    label: 'Publishing Contests!',
    to: '/publishing-contests'
  },
  {
    label: 'GGPS Presentations',
    to: '/presentations'
  },
  {
    label: 'Helpful Resources',
    to: '/resources'
  },
  {
    label: 'About the GGPS',
    to: '/about'
  }
]
</script>
