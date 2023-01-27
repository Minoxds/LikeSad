<script setup>
import PhotoCard from "./components/PhotoCard.vue";
</script>

<template>
  <header>
    <div class="navbar navbar-dark bg-dark shadow-sm">
      <div class="container d-flex justify-content-between">
        <a class="navbar-brand d-flex align-items-center" href="#"
          ><i class="fa fa-camera"></i><strong>&nbsp;minoxds</strong></a
        >
      </div>
    </div> 
  </header>
  <main role="main">
    <section class="jumbotron text-center">
      <div class="container">
        <h1>Mino's World &#9775;</h1>
        <p class="lead text-muted">
          <br />Some beautiful paths can’t be discovered without getting lost.<br />
        </p>
      </div>
    </section>
    <div class="album py-5 bg-light">
      <div class="container">
        <div class="row">
          <PhotoCard image="/Photo/IMG_20220520_125525 (1).jpg" />
          <PhotoCard image="/Photo/temple.jpg" />
          <PhotoCard image="/Photo/mess.jpg" />
          <PhotoCard image="/Photo/evening.jpg" />
          <PhotoCard image="/Photo/moon.jpg" />
          <PhotoCard image="/Photo/train.jpg" />
        </div>
      </div>
    </div>
  </main>
  <footer class="text-muted">
    <div class="container">
      <p class="float-right"><a href="#">Back To Top</a></p>
      <p>
        Let's enjoy the world of Mino.&#9774;
      </p>
      <p>
        Thank you for yout attention. &hearts;
      </p>
    </div>
  </footer>
</template>

<style scoped></style>
