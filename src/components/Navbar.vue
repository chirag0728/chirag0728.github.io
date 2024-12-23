<template>
  <header>
    <nav>
      <div class="logo">Chirag</div>
      <ul class="nav-links">
        <li><a href="#" @click.prevent="scrollTo('hero')">Home</a></li>
        <li><a href="#" @click.prevent="scrollTo('projects')">Projects</a></li>
        <li><a href="#" @click.prevent="scrollTo('footer')">Contact</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  methods: {
    scrollTo(sectionId) {
      document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth' });
    },
  },
};
</script>

<style scoped>
header {
  position: sticky;
  top: 0;
  background: rgba(0, 0, 0, 0.8);
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 10;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

.nav-links a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

.nav-links a:hover {
  color: #00ced1;
}
</style>
