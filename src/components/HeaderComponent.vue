<template>
    <header class="header">
      <div class="logo">
        <span class="company-name">Darcy Emporia</span>
      </div>
      <nav class="nav">
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/AboutUs">About</router-link></li>
          <li><router-link to="/services">Services</router-link></li>
          <li><router-link to="/contact">Contact</router-link></li>
          <li><router-link to="/features">Features</router-link></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    name: 'HeaderComponent',
  };
  </script>
  
  <style scoped>
  /* Add CSS styles for your header here */
  .header {
    background-color: #fff;
    color: #000;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 20px;
    font-family: ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;
  }

  .nav {
    text-align: center;
  }
  
  .company-name {
    font-size: 24px;
    font-weight: bold;
  }
  
  .nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    justify-content: center;
  }
  
  .nav li {
    font-size: 18px;
  }
  
  .nav a {
    color: #fff;
    text-decoration: none;
  }

  .nav li:hover {
  color: #00f; /* Change the color on hover (you can use your desired color) */
}
  </style>  