<template>
    <section class="plans">
      <h2>PLANS</h2>
      <div class="plan-cards">
        <div class="plan">
          <h3>Basic</h3>
          <p>$29</p>
          <p>Up to 20 clients</p>
          <button>Accept</button>
        </div>
        <div class="plan">
          <h3>Silver</h3>
          <p>$49</p>
          <p>Up to 50 clients</p>
          <button>Accept</button>
        </div>
        <div class="plan">
          <h3>Gold</h3>
          <p>$60</p>
          <p>Unlimited clients</p>
          <button>Accept</button>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped>
  .plans {
    text-align: center;
    padding: 2rem;
    background-color: #e6f7f8;
  }
  .plan-cards {
    display: flex;
    justify-content: center;
    gap: 1rem;
  }
  .plan {
    background-color: #00BFB2;
    color: #fff;
    padding: 1rem;
    border-radius: 0.5rem;
    width: 150px;
    text-align: center;
  }
  </style>
  