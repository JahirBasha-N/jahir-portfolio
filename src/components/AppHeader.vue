<template>
    <header>
      <h1>{{ fullName }}</h1>
      <p>{{ jobTitle }}</p>
    </header>
  </template>
  
  <script>
  export default {
    data() {
      return {
        fullName: 'Jahirbasha',
        jobTitle: 'Full Stack Developer',
      };
    },
  };
  </script>
  
  <style scoped>
  header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
  }
  
  h1 {
    margin: 0;
  }
  </style>
  