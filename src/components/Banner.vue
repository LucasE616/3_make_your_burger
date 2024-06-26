<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
  export default {
    name: 'Banner',
  }
</script>

<style scoped>
  #main-banner {
    background-image: url('/public/img/burger02.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height: 650px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
  }

  #main-banner h1 {
    color: #ededed;
    text-align: center;
    font-size: 60px;
    background-color: #363636;
    border: 2px solid #1E1E1E;
    padding: 20px 40px;
    border-radius: 8px;
  }

</style>