<template>
  <v-app>
    <MyHeader/>
    <v-main>
      <MyHero/>
      <AboutMe/>
      <MyPortfolio/>
      <MyEducation/>
      <MySkills/>
      <MyProject/>
      <ContactMe/>
      <MyFooter/>
    </v-main>
  </v-app>
</template>

<script>
import MyHeader from './components/MyHeader';
import AboutMe from './components/AboutMe.vue';
import MyHero from './components/MyHero.vue';
import MyPortfolio from './components/MyPortfolio.vue';
import MyProject from './components/MyProject.vue';
import ContactMe from './components/ContactMe.vue';
import MyFooter from './components/MyFooter.vue';
import MyEducation from './components/MyEducation.vue';
import MySkills from './components/MySkills.vue';
export default {
  name: 'App',
  components: { MyHeader, AboutMe, MyHero, MyPortfolio, MyProject, ContactMe, MyFooter, MyEducation, MySkills },
  data() {
    return {
      menus: [
          { title: "Home", route: "home" },
          { title: "About", route: "about" },
          { title: "Project", route: "project" },
          { title: "Contact", route: "contact" },
      ]
    }
  }
};
</script>
