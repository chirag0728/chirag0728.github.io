<template>
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      Offensive Security Engineer with expertise in vulnerability discovery, exploit development, and network protocol analysis.
    </p>
    <div class="about-grid">
      <div class="card">
        <h3>Skills</h3>
        <ul>
          <li>Programming Languages: C, Python, Bash, Assembly</li>
          <li>Networking: Packet analysis, TCP/IP, TLS, QUIC</li>
          <li>Security Tools: Burp Suite, Wireshark, Splunk, Metasploit</li>
        </ul>
      </div>
      <div class="card">
        <h3>Education</h3>
        <p>M.S. in Computer Science – Arizona State University | May 2027 (Estimated)</p>
        <p>B.S. in Computer Science – Arizona State University | Aug 2023</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.about {
  padding: 5rem 2rem;
  background: #121212;
  color: white;
}

.about h2 {
  text-align: center;
  margin-bottom: 2rem;
}

.about-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
}

.card {
  flex: 1 1 calc(50% - 2rem);
  background: #1e1e1e;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
}
</style>
