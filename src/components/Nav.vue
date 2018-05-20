<template>
  <nav>
    <a class="active" href="#">Lorem Ipsum</a>
    <a href="#">Home</a>
    <a href="#">About</a>
  </nav>

</template>

<script>
export default {
  name: 'app',
  data() {
    return {

    }
  }
}
</script>

<style scoped>
  nav {
    overflow: hidden;
    background-color: #664147;
  }

  nav a {
    float: left;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 19px;
  }

  nav a:hover {
    background-color: #e5f9e0;
    color: black;
  }

  nav a.active {
    background-color: #2f9c95;
    color: white;
  }
</style>
