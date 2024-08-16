<template>
    <div class="card">
      <h2>{{ title }}</h2>
      <p>{{ content }}</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Card',
    props: {
      title: String,
      content: String
    }
  }
  </script>
  
  <style scoped>
  .card {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 16px;
    margin: 16px;
    box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
  }
  </style>
  