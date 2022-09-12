<template>
  <main class="app-container">
    <div class="testimonials"><CardA /><CardB /><CardC /><CardD /><CardE /></div>
    <div class="attribution">
      Challenge by
      <a
        href="https://www.frontendmentor.io?ref=challenge"
        target="_blank"
        rel="noopener noreferrer"
        >Frontend Mentor</a
      >. Coded by
      <a
        href="https://www.frontendmentor.io/profile/VEN-github"
        target="_blank"
        rel="noopener noreferrer"
        >Raven Barrogo</a
      >.
    </div>
  </main>
</template>

<script>
import CardA from './components/CardA.vue';
import CardB from './components/CardB.vue';
import CardC from './components/CardC.vue';
import CardD from './components/CardD.vue';
import CardE from './components/CardE.vue';
export default {
  name: 'App',
  components: {
    CardA,
    CardB,
    CardC,
    CardD,
    CardE,
  },
};
</script>
