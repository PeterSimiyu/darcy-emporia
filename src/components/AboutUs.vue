<template>
    <div class="about-us">
      <div class="about-image">
        <img src="@/assets/images/about-image.jpg" alt="About Us Image" />
      </div>
      <div class="about-content">
        <h2 class="large-title">What We Do</h2>
        <p class="large-text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla vestibulum lectus id dolor auctor, ac finibus arcu scelerisque.
        </p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'AboutUs',
  };
  </script>
  
  <style scoped>
  /* Add CSS styles for your About Us component here */
  .about-us {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 50px;
    background-color: rgba(0, 0, 255, 0.2);
    font-family: ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;
  }
  
  .about-image {
    flex: 1;
  }
  
  .about-content {
    flex: 2;
    text-align: center;
  }
  
  .large-text {
    font-size: 24px; /* Adjust the font size as needed */
  }

  .large-title{
    font-size: 36px;
  }
  </style>  