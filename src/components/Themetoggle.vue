<template>
  <div class="theme-toggle">
    <button @click="toggleTheme">
      {{ darkMode ? 'Switch to Light Mode' : 'Switch to Dark Mode' }}
    </button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      darkMode: true,
    };
  },
  methods: {
    toggleTheme() {
      this.darkMode = !this.darkMode;
      document.body.classList.toggle('dark-mode', this.darkMode);
    },
  },
};
</script>

<style scoped>
.theme-toggle button {
  padding: 0.5rem 1rem;
  background: #00ced1;
  color: black;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background 0.3s ease;
}

.theme-toggle button:hover {
  background: #008080;
}
</style>
