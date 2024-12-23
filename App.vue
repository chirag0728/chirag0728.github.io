<template>
  <div id="app">
    <!-- Navigation Bar -->
    <header>
      <nav>
        <div class="logo">Chirag</div>
        <ul class="nav-links">
          <li><a href="/">Home</a></li>
          <li><a href="/experience">Experience</a></li>
          <li><a href="/resume">Resume</a></li>
        </ul>
      </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
      <h1>Welcome to My Portfolio</h1>
      <p>Showcasing my projects and experience in web development and beyond.</p>
    </section>

    <!-- Projects Section -->
    <section class="projects">
      <h2>Projects</h2>
      <div class="project-grid">
        <div class="project-card">
          <img src="/assets/images/project1.jpg" alt="Project 1">
          <h3>Project One</h3>
          <p>A short description of the project.</p>
          <a href="#">View on GitHub</a>
        </div>
        <div class="project-card">
          <img src="/assets/images/project2.jpg" alt="Project 2">
          <h3>Project Two</h3>
          <p>A short description of the project.</p>
          <a href="#">View on GitHub</a>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <p>&copy; 2024 Chirag Dewan</p>
      <div class="social-icons">
        <a href="https://github.com/yourgithub" target="_blank">GitHub</a>
        <a href="https://linkedin.com/in/yourlinkedin" target="_blank">LinkedIn</a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style scoped>
/* Base Styling */
body {
  font-family: 'JetBrains Mono', monospace;
  margin: 0;
  padding: 0;
  background: linear-gradient(to bottom, #008080, #000000);
  color: white;
}

header {
  background: rgba(0, 0, 0, 0.8);
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1rem;
}

.nav-links a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.nav-links a:hover {
  color: #00ced1;
}

.hero {
  text-align: center;
  padding: 5rem 2rem;
}

.projects {
  padding: 2rem;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1rem;
}

.project-card {
  background: #121212;
  padding: 1rem;
  border-radius: 8px;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 20px rgba(0, 206, 209, 0.5);
}

footer {
  text-align: center;
  padding: 1rem;
  background: rgba(0, 0, 0, 0.9);
  color: white;
}

footer a {
  color: white;
  margin: 0 0.5rem;
  text-decoration: none;
}

footer a:hover {
  color: #00ced1;
}
</style>
