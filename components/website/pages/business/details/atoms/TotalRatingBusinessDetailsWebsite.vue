<template>
  <div class="flex gap-1 order-1 md:order-2 items-center justify-end">
    <div
      class="flex gap-0.5"
      itemprop="starRating"
      itemscope
      itemtype="https://schema.org/Rating"
    >
      <meta itemprop="ratingValue" content="4" />
      <GenerateRatingWebsite :total-rating="3" />
    </div>

    <NuxtLink
      v-scroll-to="'#avaliations'"
      to="#"
      class="text-xs text-primary"
      rel="nofollow"
      >seja o primeiro a avaliar</NuxtLink
    >
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped></style>
