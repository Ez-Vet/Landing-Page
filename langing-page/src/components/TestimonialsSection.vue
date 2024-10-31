<template>
  <section id="testimonials" class="testimonials"> <!-- Aquí se agregó el id -->
    <h2>TESTIMONIALS</h2>
    
    <div class="testimonial-card">
      <!-- Testimonio de Maria Lopez -->
      <img src="../assets/doctor-1.png" alt="Maria Lopez" class="testimonial-image" />
      <div class="testimonial-content">
        <h4>Maria Lopez</h4>
        <p>Ez.vet has transformed our clinic. It allows us to save hours each day by managing our appointments and reminders automatically.</p>
        <div class="rating">
          ⭐⭐⭐⭐⭐
        </div>
      </div>
    </div>

    <div class="testimonial-card">
      <!-- Testimonio de Martin Jimenez -->
      <img src="../assets/doctor-2.png" alt="Martin Jimenez" class="testimonial-image" />
      <div class="testimonial-content">
        <h4>Martin Jimenez</h4>
        <p>Thanks to Ez.vet, we can offer our customers a faster and more professional service. We couldn't be happier!</p>
        <div class="rating">
          ⭐⭐⭐⭐⭐
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.testimonials {
  padding: 2rem;
  background-color: #26d0c3;
  color: #fff;
  text-align: center;
}

.testimonials h2 {
  font-size: 2rem;
  margin-bottom: 2rem;
}

.testimonial-card {
  display: flex;
  align-items: center;
  background-color: #8BDCD6;
  color: #000000;
  padding: 1.5rem;
  margin: 1rem 0;
  border-radius: 15px;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

.testimonial-image {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-right: 1rem;
  flex-shrink: 0;
}

.testimonial-content {
  text-align: left;
}

.testimonial-content h4 {
  margin: 0;
  font-size: 1.2rem;
  color: #000000;
}

.testimonial-content p {
  margin: 0.5rem 0;
  color: #333;
}

.rating {
  color: #ffcc00;
  font-size: 1.2rem;
}
</style>
