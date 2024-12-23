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
      <p>Showcasing my coding projects and experience in technology.</p>
    </section>

    <!-- Projects Section -->
    <section class="projects">
      <h2>Projects</h2>
      <div class="project-card">
        <img src="/assets/images/project1.jpg" alt="Project 1">
        <h3>Project One</h3>
        <p>A short description of this project, its purpose, and the technology used.</p>
        <a href="#" target="_blank">View More</a>
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
  background-size: 400% 400%;
  animation: gradientBG 15s ease infinite;
  color: white;
}

@keyframes gradientBG {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
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
  transition: color 0.3s;
}

.nav-links a:hover {
  color: #00ced1;
}

.hero {
  text-align: center;
  padding: 5rem 2rem;
}

.hero h1 {
  font-size: 3rem;
  text-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
}

.hero p {
  font-size: 1.2rem;
  margin-top: 1rem;
}

.projects {
  padding: 2rem;
}

.project-card {
  background: #121212;
  padding: 1rem;
  border-radius: 8px;
  text-align: center;
  margin: 1rem auto;
  width: 90%;
  max-width: 400px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 6px 30px rgba(0, 206, 209, 0.5);
}

.project-card img {
  max-width: 100%;
  border-radius: 8px;
}

.project-card h3 {
  margin: 1rem 0 0.5rem;
}

.project-card p {
  font-size: 0.9rem;
  color: #cccccc;
}

.project-card a {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.5rem 1rem;
  color: white;
  text-decoration: none;
  border: 1px solid #00ced1;
  border-radius: 4px;
  transition: all 0.3s ease;
}

.project-card a:hover {
  background: #00ced1;
  color: black;
}

footer {
  text-align: center;
  padding: 1rem;
  background: rgba(0, 0, 0, 0.9);
  color: white;
}

footer .social-icons a {
  margin: 0 1rem;
  text-decoration: none;
  color: white;
  font-weight: bold;
  transition: color 0.3s;
}

footer .social-icons a:hover {
  color: #00ced1;
}
</style>
