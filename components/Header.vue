<template>
  
    <div class="center examplex">
      <vs-navbar center-collapsed v-model="active">
        <template #left>
          <img src="../assets/images/logos/NoMVP_Orange.png" alt="">
        </template>
        <vs-navbar-item :active="active == 'contact'" id="contact">
        <NuxtLink class='nav-link' to ='/contact'>Contact</NuxtLink>
        </vs-navbar-item>
        <vs-navbar-item :active="active == 'about'" id="about">
        <NuxtLink class='nav-link' to ='/about'>About Us</NuxtLink>
        </vs-navbar-item>
        <vs-navbar-item :active="active == 'nav-link'" id="nav-link">
        <NuxtLink class='nav-link' to ='#'>nav-link</NuxtLink>
        </vs-navbar-item>
        <vs-navbar-item :active="active == 'nav-link'" id="nav-link">
        <NuxtLink class='nav-link' to ='#'>nav-link</NuxtLink>
        </vs-navbar-item>
        <template #right>
          <vs-button flat >Login</vs-button>
          <vs-button>Get Started</vs-button>
        </template>
      </vs-navbar>
      <div class="square">
        <div class="child">
          child 1
        </div>
        <div class="child">
          child 2
        </div>
        <div class="child">
          child 3
        </div>
      </div>

    
    <!-- <NuxtLink to="/">Home</NuxtLink>
    <NuxtLink to="/contact">Contact</NuxtLink>
    <NuxtLink to="/about">About Us</NuxtLink> -->

  </div>
</template>

<script>
export default {};
</script>

<style scoped>

.nav-link{
  text-decoration: none;
  color: var(--vs-dark);
}

.vs-navbar__item{
  opacity: 1;
  color: var(--vs-primary);
}
</style>
