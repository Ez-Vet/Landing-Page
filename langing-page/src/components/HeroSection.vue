<template>
  <section class="hero">
    <div class="hero-content">
      <!-- Imagen de la mascota -->
      <img src="../assets/dog-cat.png" alt="Dog and Cat" class="hero-image" />

      <!-- Texto descriptivo -->
      <div class="hero-text">
        <h1>PLATFORM THAT SIMPLIFIES VETERINARY MANAGEMENT</h1>
        <p>Optimize your processes, save time and provide better care to your patients.</p>
        <button class="cta-button">INICIAR SESIÓN</button>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero {
  width: 99vw;
  height: 99vh;
  background-color: #26d0c3;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0;
  margin: 0;
  overflow: hidden;
  box-sizing: border-box;
}

.hero-content {
  display: flex;
  align-items: center;
  justify-content: space-between; /* Distribuye el espacio entre imagen y texto */
  max-width: 1400px;             /* Ajusta el ancho máximo de la sección */
  width: 100%;
  padding: 0 3rem;
  gap: 3rem;
}

.hero-image {
  width: 50%;                    /* Ocupa el 50% del espacio */
  max-width: 600px;              /* Limita el tamaño máximo en pantallas grandes */
  height: auto;
}

.hero-text {
  flex: 1;                       /* El texto ocupa el espacio restante */
  text-align: left;
}

.hero-text h1 {
  font-size: 2.8rem;
  line-height: 1.2;
  margin-bottom: 1rem;
  color: #fff;
}

.hero-text p {
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
  color: #e6f7f8;
  max-width: 500px;              /* Limita el ancho del párrafo */
}

.cta-button {
  background-color: #fff;
  color: #26d0c3;
  border: none;
  padding: 0.75rem 1.5rem;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
  font-size: 1rem;
}

.cta-button:hover {
  background-color: #4a3083;
  color: #fff;
}
</style>
