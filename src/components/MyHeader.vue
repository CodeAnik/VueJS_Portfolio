<template>
  <v-app-bar
      style="padding: 0px 40px"
      app
      color="success"
      light
      elevation='5'
      elevate-on-scroll
    >
    
    <v-toolbar-title>
      <img src="../assets/logo.svg" alt="logo" width="50%">
    </v-toolbar-title>
      <v-spacer/>
      <v-list class="d-flex align-center transparent">
        <v-list-item class="mx-3" link v-for="(menu, index,) in menus" :key="index" :to="menu.route">
          <v-list-item-title class="navmenu">{{menu.title}}</v-list-item-title>
        </v-list-item>
        <v-btn color="success">HIRE ME</v-btn>
      </v-list>
    </v-app-bar>
</template>

<script>
  export default {
    name: 'MyHeader',
    data() {
    return {
      menus: [
          { title: "Home", route: "home" },
          { title: "About", route: "about"},
          { title: "Portfolio", route: "portfolio" },
          { title: "Project", route: "project" },
          { title: "Contact", route: "contact" },
      ]
    }
  }
}
</script>

<style>
  .v-list-item__title.navmenu {
    font-size: 18px;
    font-weight: 500;
    color: white;
}
</style>
