<template>
  <footer id="footer">
    <p>
      Developed by <a href="https://www.instagram.com/lucase616/" target="_blank">Lucas E.</a> &copy; 2024.
    </p>
  </footer>
</template>

<script>
  export default {
    name: 'Footer',
  }
</script>

<style scoped>
  #footer {
    height: 200px;
    background-color: #1E1E1E;
    border-top: 4px solid #08070B;
    color: #ffbb00;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
  }

  #footer p a {
    color: #ffbb00;
    transition: .5s;
  }

  #footer p a:hover {
    color: #ededed;
  }

</style>