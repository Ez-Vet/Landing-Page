<template>
  <footer class="footer">
    <p>©2024 ez.vet. Todos los derechos reservados.</p>
    <div class="social-icons">
      <a href="https://instagram.com" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-instagram"></i>
      </a>
      <a href="https://twitter.com" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-twitter"></i>
      </a>
      <a href="https://facebook.com" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-facebook"></i>
      </a>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background-color: #4a3083;
  color: #fff;
  font-size: 1rem;
}

.social-icons {
  display: flex;
  gap: 1rem;
}

.social-icons a {
  color: #fff;
  font-size: 1.5rem;
  transition: color 0.3s;
}

.social-icons a:hover {
  color: #26d0c3;
}
</style>
