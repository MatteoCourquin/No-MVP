<template>
  <div class="navbar">
        <img class="logo" src="../assets/images/logos/NoMVP_Orange.png" alt="logo">

        <NuxtLink class='nav-link' to ='/contact'>Contact</NuxtLink>
        <NuxtLink class='nav-link' to ='/about'>About Us</NuxtLink>
        <NuxtLink class='nav-link' to ='#'>nav-link</NuxtLink>
        <NuxtLink class='nav-link' to ='#'>nav-link</NuxtLink>
        <!-- <vs-button flat >Login</vs-button> -->
  </div>
</template>

<script>
export default {};
</script>

<style scoped>

.vs-navbar{
  padding: 0 !important;
}

.navbar{
  position: relative;
}

.logo{
  width: 100px;
  margin: 20px;
}

.nav-link{
  color: var(--vs-dark);
}

.nav-link:hover{
  color: var(--vs-primary);
  transition: 0.2s;
}

.vs-navbar__item{
  opacity: 1;
  color: var(--vs-primary);
}
</style>
