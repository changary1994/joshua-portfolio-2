<template>
  <nav>
    <div class="link-container">
      <router-link to="/">News</router-link>
      <router-link to="/guides">Guides</router-link>
      <router-link to="/reviews">Reviews & Previews</router-link>
      <router-link to="/features">Features</router-link>
    </div>
  </nav>
</template>

<style scoped>
nav {
  background-color: #0b6aa0;
  padding: 10px;
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  text-align: center;
}

nav a {
  font-weight: bold;
  color: white;
  margin-left: 3%;
  text-decoration: none;
  font-weight: 400;
}

nav a.router-link-exact-active {
  color: #fff371;
}
</style>
