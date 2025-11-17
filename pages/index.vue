<template>
  <div class="container">
    <header>
      <h1>Welcome to poojaclouds ☁️</h1>
      <img src="/images/IMG_20251117_122438.jpg" alt="pooja" class="profile-image" />
      <p>Your one-stop platform for AWS & DevOps learning</p>
    </header>

    <main>
      <section>
        <h2>🚀 About This Project</h2>
        <p>
          This website is powered by <strong>Nuxt 3</strong> and deployed using
          <strong>Jenkins CI/CD</strong>, <strong>PM2</strong>, and <strong>AWS EC2</strong>.
        </p>
      </section>

      <section>
        <h2>🌐 Latest Updates</h2>
        <ul>
          <li>✔️ SSL Enabled with Nginx</li>
          <li>✔️ CI/CD via Jenkins Pipeline</li>
          <li>✔️ Live Deployment on EC2</li>
        </ul>
      </section>
    </main>

    <footer>
      <p>© {{ new Date().getFullYear() }} AmbzClouds. All rights reserved.</p>
    </footer>
  </div>
</template>

<script setup>
</script>

<style scoped>
.profile-image {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  display: block;
  margin: 20px auto;
  object-fit: cover;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

h1 {
  color: #2563eb;
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}

section {
  margin-top: 2rem;
  background: #f9fafb;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
}

footer {
  margin-top: 3rem;
  color: #666;
}
</style>
