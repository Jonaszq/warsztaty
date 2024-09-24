<template>
    <header class="header">
      <div class="contact-list">
        <a href="https://github.com/Jonaszq" target="_blank" class="contact-item">
          GitHub
        </a>
        <a href="mailto:kenojyt@gmail.com" class="contact-item">
          Email
        </a>
      </div>
    </header>
  </template>
  
  <style scoped>
  .header {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin-bottom: 16px;
    padding: 20px;
    background: linear-gradient(to right, #0B1C3C, #1E488F);
    color: #ffffff;
    border-radius: 8px;
    max-width: 1200px;
    width: 100%;
    max-height: 400px;
    height: 100%;
  }
  h1 {
    font-size: 4rem;
    margin-bottom: 10px;
    text-shadow: 0 0 3px #000000;
  }
  h2 {
    font-size: 2rem;
    color: #76c7c0;
    text-shadow: 0 0 3px #000000;
  }
  .contact-list {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
  }
  .contact-item {
    display: flex;
    align-items: center;
    color: #ffffff;
    text-decoration: none;
    font-size: 1.2rem;
    text-shadow: 0 0 3px #000000;
  }
  .contact-item i {
    margin-right: 8px;
    font-size: 1.5rem;
    text-shadow: 0 0 3px #000000;
  }
  .contact-item:hover {
    color: #A3CFFF;
  }
  </style>