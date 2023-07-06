
<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <div class="sidebar">
    <div class="sidebar-content">
      <div class="image-container">
        <img src="/images/louise.jpg" alt="Photo">
      </div>
      <h1>Louise Schmidtgen</h1>
      <h2>Backend Software Engineer</h2>
      <ul>
        <li>
          <i class="fa fa-github"></i>
          <a href="https://github.com/louiseschmidtgen/" target="_blank">louiseschmidtgen</a>
        </li>
        <li>
          <i class="fa fa-linkedin"></i>
          <a href="https://www.linkedin.com/in/louise-schmidtgen-6a8402180/" target="_blank">louise-schmidtgen</a>
        </li>
        <li>
          <i class="fa fa-instagram"></i>
          <a href="https://www.instagram.com/lulu_10.8/" target="_blank">lulu_10.8</a>
        </li>
        <li>
          <i class="fa fa-envelope"></i>
          <a href="mailto:louise.schmidtgen@gmail.com">louise.schmidtgen@gmail.com</a>
        </li>
        <li>
          <i class="fa fa-map-pin"></i>
          <p>Savery, Wyoming</p>
        </li>
      </ul>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'SideBar',
});
</script>

<style scoped>
.sidebar {
  max-width: 400px;
  width: 100%;
  padding: 20px;
}

/* Adjust the width as needed */
img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin: 0 auto;
  display: block;
}

i {
  font-size: 20px;
  margin-right: 10px;
  background-color: #FDCEDF;
  padding: 8px;
  border-radius: 50%;
}

h1 {
  font-size: 24px;
  margin-bottom: 10px;
  text-align: center;
}

h2 {
  font-size: 18px;
  margin-bottom: 20px;
  text-align: center;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}

i {
  font-size: 20px;
  margin-right: 10px;
}

a {
  font-size: 16px;
  word-break: break-all; /* Ensure long email addresses wrap to a new line */
}

</style>
