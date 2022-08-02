<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo animate-bounce" src="@/assets/two-dogs.png" width="125" height="125" />
    <!-- <div class="logo"></div> -->
    <div class="wrapper">
      <HelloWorld msg="Bella & Mishka" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}
.logo {
  display: block;
  margin: 0 auto 2rem;
}
/* 
.logo {
 width: 100%;
 height: 50%;
  background: url("./assets/two-dogs.png") no-repeat;
background-size: contain;
}
.logo:hover {
  width: 100%;
  height: 50%;
  
  background: url("./assets/cute-dog.png") no-repeat;
  background-size: contain;
} */

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

/* .logo {
 width: 100%;
 height: 50%;
  background: url("./assets/two-dogs.png") no-repeat;
background-size: contain;
}
.logo:hover {
  width: 100%;
  height: 50%;
  
  background: url("./assets/cute-dog.png") no-repeat;
  background-size: contain;
} */
  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
