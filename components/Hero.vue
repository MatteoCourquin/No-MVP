<template>
  <div class="hero">

    <div class="section-text">
      <h1>TITRE H1</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ac nam massa vitae nunc pellentesque augue proin. Feugiat eu in arcu, dictum. Fames mi aliquet eleifend purus, habitant nibh. Sed quisque integer pretium nec tincidunt non blandit ultrices neque.
      </p>

      <button class="btn-orange">
        Get Started
      </button>
    </div>

    <div class="section-image">

      <img src="../assets/images/undraw_building_websites_i78t 1.svg" alt="">

    </div>

  </div>
</template>

<script>
export default {};
</script>

<style scoped>

.hero {
  display: grid;
  grid-template-columns: 1fr 1fr;
  height: 65vh;
  margin-bottom: 20vh;
}

.section-text {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.section-text > p {
  width: 500px;
  margin: 40px;
}

.section-image {
  display: flex;
  align-items: center;
  justify-content: center; 
}

/* ---------------- Responsive ---------------- */

@media screen and (max-width: 1200px) {
  .hero{
    grid-template-columns: 1fr;
  }
  .section-image{
    margin: 50px 0 40px 0;
  }
  .section-text > p {
    width: 80%;
    margin: 40px;
}
}

</style>
