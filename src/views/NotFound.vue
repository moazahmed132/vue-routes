<template>
  <h2>404</h2>
  <h4>Page doesn't exist</h4>
  <div class="notfoud">
    <router-link to="/"><h2>Go Home</h2></router-link>
  </div>
</template>

<style>
.notfoud h2 {
  background: #f4f4f4;
  padding: 20px;
  border-radius: 10px;
  margin: 10px auto;
  max-width: 600px;
  cursor: pointer;
  color: #444;
}
.notfoud h2:hover {
  background: #ddd;
}
.notfoud a {
  text-decoration: none;
}
</style>
