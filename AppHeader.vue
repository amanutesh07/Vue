<template>
  <header id="home">
    <nav id="nav-wrap">
      <a class="mobile-btn" href="#nav-wrap" title="Show navigation">Show navigation</a>
      <a class="mobile-btn" href="#" title="Hide navigation">Hide navigation</a>
      <ul id="nav" class="nav">
        <li class="current"><a class="smoothscroll" href="#home">Home</a></li>
        <li><a class="smoothscroll" href="#about">About</a></li>
        <li><a class="smoothscroll" href="#resume">Resume</a></li>
        <li><a class="smoothscroll" href="#testimonials">Mottoes</a></li>
        <li><a class="smoothscroll" href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="row banner">
      <div class="banner-text">
        <h1 class="responsive-headline">I'm Duman Baltabay.</h1>
        <h3>I'm a Almaty based backend developer. Let's start scrolling and learn more about me.</h3>
        <hr />
        <ul class="social">
          <li><a href="https://github.com/dmnblt"><i class="fa fa-github"></i></a></li>
          <li><a href="#"><i class="fa fa-google-plus"></i></a></li>
          <li><a href="#"><i class="fa fa-linkedin"></i></a></li>
          <li><a href="#"><i class="fa fa-instagram"></i></a></li>
          <li><a href="#"><i class="fa fa-skype"></i></a></li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppHeader"
}
</script>

<style scoped>

</style>