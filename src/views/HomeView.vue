<script setup>
import Hero from '@/components/Hero.vue';
import HomeCards from '@/components/HomeCards.vue';
import JobListings from '@/components/JobListings.vue';
</script>

<template>
  <Hero
    title="Become a Vue Dev"
    subtitle="Find a Vue job that fits your skills"
  />
  <HomeCards />
  <JobListings :limit="3" :show-button="true" />
</template>

<style></style>
