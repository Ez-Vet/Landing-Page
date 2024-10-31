<template>
    <section class="hero">
      <div class="hero-content">
        <!-- Imagen de la mascota -->
        <img src="../assets/dog-cat.png" alt="Dog and Cat" class="hero-image" />
  
        <!-- Texto descriptivo -->
        <div class="hero-text">
          <h1>PLATAFORM THAT SIMPLIFIES VETERINARY MANAGEMENT</h1>
          <p>Optimize your processes, save time and provide better care to your patients.</p>
          <button class="cta-button">INICIAR SESIÓN</button>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped>
  .hero {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #26d0c3;
    padding: 3rem 1rem;
    color: #fff;
    text-align: left;
  }
  
  .hero-content {
    display: flex;
    align-items: center;
    max-width: 1200px;
    gap: 2rem;
  }
  
  .hero-image {
    width: 45%;
    max-width: 500px;
    height: auto;
  }
  
  .hero-text {
    flex: 1;
  }
  
  .hero-text h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
  }
  
  .hero-text p {
    font-size: 1.25rem;
    margin-bottom: 1.5rem;
  }
  
  .cta-button {
    background-color: #fff;
    color: #26d0c3;
    border: 1px solid #26d0c3;
    padding: 0.75rem 1.5rem;
    font-weight: bold;
    border-radius: 5px;
    cursor: pointer;
  }
  
  .cta-button:hover {
    background-color: #4a3083;
    color: #fff;
  }
  </style>
  