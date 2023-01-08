<template>
  <section>
    <CardPerfume />
  </section>
</template>

<script>
import CardPerfume from '../components/CardPerfume.vue'

export default {
  name: 'Home',
  components: {
    CardPerfume,
  }
}
</script>

<style scoped>
  section {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh
  }

</style>