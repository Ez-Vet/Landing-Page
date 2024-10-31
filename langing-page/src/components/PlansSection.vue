<template>
  <section id="plans" class="plans"> <!-- Agregamos id="plans" aquí -->
    <h2>PLANS</h2>
    <div class="plans-cards">
      <!-- Tarjeta BASIC -->
      <div class="plan-card">
        <h3>BASIC</h3>
        <p class="price">$29</p>
        <ul>
          <li>Up to 20 clients</li>
          <li>Basic clinical history</li>
        </ul>
        <button>Accept</button>
      </div>

      <!-- Tarjeta SILVER -->
      <div class="plan-card">
        <h3>SILVER</h3>
        <p class="price">$49</p>
        <ul>
          <li>Up to 50 clients</li>
          <li>Advanced clinical history</li>
        </ul>
        <button>Accept</button>
      </div>

      <!-- Tarjeta GOLD -->
      <div class="plan-card">
        <h3>GOLD</h3>
        <p class="price">$60</p>
        <ul>
          <li>Unlimited clients</li>
          <li>Complete clinical history</li>
        </ul>
        <button>Accept</button>
      </div>
    </div>
  </section>
</template>

<style scoped>
.plans {
  width: 99vw;
  height: 80vh;
  background-color: #fff;
  text-align: center;
  position: relative;
  background-image: url('../assets/loros.png'); /* Imagen de los loros */
  background-repeat: no-repeat;
  background-position: center bottom; /* Centra la imagen en la parte inferior */
  background-size: contain; /* Ajusta el tamaño de la imagen al contenedor */
}

.plans h2 {
  font-size: 2rem;
  margin-bottom: 1.5rem;
}

.plans-cards {
  display: flex;
  justify-content: center;
  gap: 1.5rem;
}

.plan-card {
  background-color: #26d0c3;
  color: #fff;
  padding: 1.5rem;
  border-radius: 10px;
  width: 250px;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
  position: relative;
  z-index: 1; /* Asegura que las tarjetas estén sobre el fondo */
}

.plan-card h3 {
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
}

.price {
  font-size: 2rem;
  font-weight: bold;
  margin: 0.5rem 0;
}

.plan-card ul {
  list-style: none;
  padding: 0;
  margin: 1rem 0;
}

.plan-card li {
  margin: 0.5rem 0;
}

.plan-card button {
  background-color: #bfc4ff;
  color: #4a3083;
  border: none;
  padding: 0.5rem 1rem;
  font-weight: bold;
  border-radius: 5px;
  cursor: pointer;
}

.plan-card button:hover {
  background-color: #fff;
}
</style>
