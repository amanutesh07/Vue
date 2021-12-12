<template>
  <div id="app">
    <AppHeader/>
    <AppAbout/>
    <Resume/>
    <Mottoes/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import Vue from 'vue';
import AppHeader from "./components/AppHeader.vue";
import AppAbout from "./components/AppAbout.vue";
import Resume from "./components/Resume.vue";
import Mottoes from "./components/Mottoes.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export  default   {
  components:{Footer, Mottoes, AppHeader, AppAbout,Resume, Contact}
}
</script>