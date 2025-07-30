<script setup>
import Hero from '@/components/Hero.vue';
import HomeCards from '@/components/HomeCards.vue';
import JobListings from '@/components/JobListings.vue';

</script>

<template>
  <Hero title="just a test title" subtitle="just a test subtitle"/>
  <HomeCards />
  <JobListings  :limit="3" :showButton="true" />
  
</template>