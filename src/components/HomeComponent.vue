<template>
    <div class="home-container">
      <div class="home-content">
        <h1>WELCOME TO DARCY EMPORIA</h1>
        <p>Taking care of your trading needs</p>
      </div>
    </div>
  </template>
  
  <style scoped>
  .home-container {
    height: 100vh;
    background-image: url(@/assets/images/home-background.jpg);
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .home-content {
    text-align: center;
    color: #fff;
    font-family: ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;
    background-color: rgba(0, 0, 0, 0.5);
    padding: 200px;
    border-radius: 40px;
  }
  
  h1 {
    font-size: 48px;
    margin-bottom: 16px;
  }
  
  p {
    font-size: 24px;
  }
  </style>  