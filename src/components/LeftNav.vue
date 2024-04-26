<template>
  <div class="nav-wrapper">
    <div class="photo-container">
      <img alt="Vue logo" src="../assets/josh_portfolio.jpg" class="photo" />
    </div>
  </div>
</template>

<style scoped>
/* TODO: ADD CSS that will change nav bar to full page when the viewport is minimized to a certain width */
.nav-wrapper {
  position: fixed;
  top: 0;
  left: 0;
  width: 275px;
  height: 100%;
  background: url(@/assets/nav-background.webp);
  background-size: cover;
}

.photo-container {
  margin: auto;
  margin-top: 50px;
  border-radius: 50%;
  width: 150px; /* Adjust as needed */
  height: 150px; /* Adjust as needed */
  overflow: hidden;
}
.photo {
  width: 100%; /* Ensure the image fills the container */
  height: 100%; /* Ensure the image fills the container */
  object-fit: cover;
}
</style>
