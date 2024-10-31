<template>
    <header class="header">
      <div class="logo">ez.Vet</div>
      <nav class="nav">
        <a href="#about" class="nav-link">ABOUT US</a>
        <a href="#plans" class="nav-link">PLANS</a>
        <a href="#testimonials" class="nav-link">TESTIMONIALS</a>
      </nav>
      <button class="login-button">INICIAR SESIÓN</button>
    </header>
  </template>
  
  <style scoped>
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
    background-color: #4a3083;
    color: #fff;
  }
  
  .logo {
    font-size: 1.5rem;
    font-weight: bold;
    color: #fff;
  }
  
  .nav {
    display: flex;
    gap: 1.5rem;
  }
  
  .nav-link {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
  }
  
  .nav-link:hover {
    color: #26d0c3;
  }
  
  .login-button {
    background-color: #fff;
    color: #4a3083;
    border: 1px solid #4a3083;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold;
  }
  
  .login-button:hover {
    background-color: #26d0c3;
    color: #fff;
  }
  </style>
  