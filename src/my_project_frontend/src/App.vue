
<template>
  <div id="app" class="app-container">
  <Header />
  
  <Projects />
  <Skills />
  <aboutYou />
  <Contact />
</div>
</template>

<script>
import Header from './components/Header.vue';
import aboutYou from './components/aboutYou.vue';
import Projects from './components/Projects.vue';
import Skills from './components/Skills.vue';
import Contact from './components/Contact.vue';


export default {
  name: 'App',
  components: {
    Header,
    aboutYou,
    Projects,
    Skills,
    Contact,
  },
};

</script>