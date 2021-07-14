<template>
  <div class="menu">
    <header>
      <router-link to="/Dashboard">Dashboard</router-link> /
      <router-link to="/about">About</router-link> /
      <router-link to="/NotFound">NotFound</router-link> /
      <!--<button @click="goToThePageNotFound">Not Found</button>-->
    </header>
    <router-view />
  </div>
</template>

<script>
//import list from "@/data";

export default {
  name: "App",
};
</script>


