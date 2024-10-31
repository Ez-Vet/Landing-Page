<template>
  <section class="testimonials">
    <h2>TESTIMONIALS</h2>
    <div class="testimonial-card">
      <!-- Testimonio de Maria Lopez -->
      <img src="../assets/" alt="Maria Lopez" class="testimonial-image" />
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
      <img src="@/assets/doctor2.png" alt="Martin Jimenez" class="testimonial-image" />
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

.testimonial-card {
  display: flex;
  align-items: center;
  background-color: #e6f7f8;
  color: #26d0c3;
  padding: 1rem;
  margin: 1rem 0;
  border-radius: 0.5rem;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

.testimonial-image {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-right: 1rem;
}

.testimonial-content {
  text-align: left;
}

.testimonial-content h4 {
  margin: 0;
  font-size: 1.1rem;
}

.testimonial-content p {
  margin: 0.5rem 0;
}

.rating {
  color: #ffcc00;
  font-size: 1rem;
}
</style>
