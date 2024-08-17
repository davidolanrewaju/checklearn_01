<script setup>
  import NavigationBar from '@/components/NavigationBar.vue';
  import HeroSection from '@/components/HeroSection.vue';
  import HomeCards from '@/components/HomeCards.vue';
  import JobListings from '@/components/JobListings.vue';
</script> 

<template>
  <NavigationBar />
  <HeroSection />
  <HomeCards />
  <JobListings :show-button="true" />
</template>
