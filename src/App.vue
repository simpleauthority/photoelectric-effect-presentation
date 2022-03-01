<script setup>
import PresentationContainer from './components/PresentationContainer.vue';
import TitleSlide from './components/slides/TitleSlide.vue';
import TopicOverview from './components/slides/TopicOverview.vue';
import FirstTopicSlide from './components/slides/FirstTopicSlide.vue';
import TopicOverviewReminder from './components/slides/TopicOverviewReminder.vue';
import SecondTopicSlide from './components/slides/SecondTopicSlide.vue';
import FinalTopicOverview from './components/slides/FinalTopicOverview.vue';
import FinalTopicSlide from './components/slides/FinalTopicSlide.vue';
import TopicOverviewRecap from './components/slides/TopicOverviewRecap.vue';

const bigIdeas = [
  "What is the photoelectric effect?",
  "Why should I care about it?",
  "How can Planck's constant be derived using it?"
]
</script>

<template>
  <PresentationContainer id="#app">
    <TitleSlide />
    <TopicOverview :bigIdeas="bigIdeas" />
    <FirstTopicSlide />
    <TopicOverviewReminder :bigIdeas="bigIdeas" />
    <SecondTopicSlide />
    <FinalTopicOverview :bigIdeas="bigIdeas" />
    <FinalTopicSlide />
    <TopicOverviewRecap :bigIdeas="bigIdeas" />
  </PresentationContainer>
</template>

<style>
#app {
  margin-top: 20px;
  height: 90vh;
}
</style>

