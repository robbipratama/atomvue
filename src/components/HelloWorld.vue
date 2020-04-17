<template>
  <div class="hello">
    <nav class="navbar">
      <a class="navbar-brand">E-BERITA</a>
      <a class="navbar" href="#">Home</a>
      <a class="navbar" href="#">Blog</a>
      <a class="navbar" href="#">About Us</a>
      <a class="navbar" href="#" onClick="return confirm ('Yakin?')">Logout</a>
      <form class="form-inline">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.kaki
{
  background: red;
}
.navbar {
  background-color: black;
}
.navbar-brand{
  color: white;
}
.btn-outline-success{
  background-color: rgb(2, 165, 2);
  color: black;
}
.btn-outline-success:hover{
  background-color: black;
  color: white;
}
</style>
