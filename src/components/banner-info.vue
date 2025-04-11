<template>
    <section class="hero  md:bg-[url(../assets/images/banner-img.png)] object-cover h-svh bg-no-repeat">
      <div class="hero-content">
        <div class="text-block">
          <p>Санкт-Петербург</p>
          <h1>Котейка</h1>
          <p>Уютная гостиница для котов и кошек</p>
          <button>Забронировать</button>
        </div>
      </div>
    </section>
  </template>
  
  <script setup>
  
  </script>
  
  <style scoped>
  .hero {
    padding: 100px 40px 60px;
  }
  
  .hero-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    padding-left: 198px;
  }
  
  .text-block {
    max-width: 400px;
  }
  
  .text-block h1 {
    font-size: 3rem;
    margin-bottom: 10px;
    color:#1A212F;
    font-weight: 500;
  }
  
  .text-block p {
    font-size: 1.2rem;
    margin-bottom: 20px;
    color: #1A212F;
  }
  
  button {
    background-color:white;
    color:#1A212F;
    border: none;
    padding: 12px 24px;
    border-radius: 8px;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 25px;
  }
  

  </style>