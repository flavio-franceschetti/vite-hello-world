<script>
export default {
  name: "Jumbotron",
};
</script>

<template>
  <div class="container">
    <h1>Non smettere mai di esplorare .</h1>
    <a href="#">ESPLORA ADESSO</a href="#">
  </div>
</template>

<style scoped>
.container {
  height: 100vh;
  background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.8)),
    url(../../public/2.jpg);
  background-size: cover;
  align-content: center;
  text-align: center;
}

h1 {
  color: #fff;
  font-family: cursive;
  font-size: 50px;
}

a {
    font-family: Arial, Helvetica, sans-serif;
display: inline-block;
  margin-top: 20px;
  font-weight: bold;
  font-size: 18px;
  color: #fff;
  border: none;
  background: none;
  border: 2px solid #fff;
  padding: 20px 30px;
  text-decoration: none;
}

a:hover {
  color: black;
  background-color: #fff;
  cursor: pointer;
}
</style>
