<template>
    <footer class="footer">
      <p>© {{ year }} Mi Sitio Web. Todos los derechos reservados.</p>
    </footer>
  </template>
  
  <script>
  export default {
    data() {
      return {
        year: new Date().getFullYear()
      };
    }
  };
  </script>
  
  <style scoped>
  .footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 15px;
    position: relative;
    width: 100%;
  }
  </style>