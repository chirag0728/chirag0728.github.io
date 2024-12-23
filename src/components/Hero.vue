<template>
  <section class="hero">
    <img src="/assets/images/background.jpg" alt="Background" class="hero-background" />
    <div class="hero-content">
      <h1>Hi, I'm Chirag Dewan</h1>
      <p>Offensive Security Engineer | Vulnerability Researcher</p>
      <button @click="scrollToAbout">Learn More</button>
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    scrollToAbout() {
      document.getElementById('about').scrollIntoView({ behavior: 'smooth' });
    },
  },
};
</script>

<style scoped>
.hero {
  position: relative;
  text-align: center;
  color: white;
  padding: 5rem 2rem;
}

.hero-background {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  filter: brightness(50%);
}

.hero-content h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.hero-content button {
  padding: 0.8rem 1.5rem;
  border: none;
  background: #00ced1;
  color: #000;
  font-weight: bold;
  border-radius: 4px;
  cursor: pointer;
}
</style>
