<template>
  <div class="header">
    <img
      class="logo"
      src="../assets/images/logos/NoMVP_Orange.png"
      alt="logo"
    />

    <div class="navbar">
      <NuxtLink class="nav-link" to="/contact">Contact</NuxtLink>
      <NuxtLink class="nav-link" to="/about">About Us</NuxtLink>
      <NuxtLink class="nav-link" to="#">nav-link</NuxtLink>
      <NuxtLink class="nav-link" to="#">nav-link</NuxtLink>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.header {
  position: relative;
  display: flex;
  justify-content: space-between;
  height: 15vh;
}

.navbar {
  margin-top: 60px;
  margin-right: 30px;
}

.logo {
  width: 90px;
  height: 90px;
  margin: 30px;
}

.nav-link {
  color: var(--grey);
  margin: 30px;
}

@media screen and (max-width: 700px) {
  .navbar {
    display: none;
  }
  .menu-bg {
    display: block;
  }
}
</style>
