<template>
  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="project-card">
      <img src="/assets/images/project1.jpg" alt="Project One">
      <h3>Project One</h3>
      <p>A short description of this project, its purpose, and the technology used.</p>
      <div class="tech-tags">
        <span>Python</span>
        <span>Networking</span>
        <span>C</span>
      </div>
      <a href="#" target="_blank">View More</a>
    </div>
  </section>
</template>

<style scoped>
.projects {
  padding: 4rem 2rem;
  background: linear-gradient(to bottom, #000000, #008080);
  color: white;
}

.project-card {
  background: #121212;
  padding: 2rem;
  margin: 1rem auto;
  max-width: 600px;
  border-radius: 8px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 6px 20px rgba(0, 206, 209, 0.5);
}

.tech-tags span {
  display: inline-block;
  margin: 0.2rem;
  padding: 0.2rem 0.5rem;
  background: #00ced1;
  color: black;
  border-radius: 5px;
  font-size: 0.8rem;
}
</style>
