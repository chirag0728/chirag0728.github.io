<template>
  <footer id="footer">
    <p>&copy; 2024 Chirag Dewan</p>
    <div class="social-icons">
      <a href="https://github.com/chirag0728" target="_blank">
        <img src="/assets/icons/github.svg" alt="GitHub">
      </a>
      <a href="mailto:chirag0728@gmail.com" target="_blank">
        <img src="/assets/icons/email.svg" alt="Email">
      </a>
      <a href="https://linkedin.com/in/chiragdewan" target="_blank">
        <img src="/assets/icons/linkedin.svg" alt="LinkedIn">
      </a>
    </div>
  </footer>
</template>

<style scoped>
footer {
  text-align: center;
  padding: 2rem;
  background: #121212;
}

.social-icons img {
  width: 24px;
  margin: 0 0.5rem;
  transition: transform 0.3s ease;
}

.social-icons img:hover {
  transform: scale(1.2);
}
</style>
