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

      <img src="../assets/images/logoHero.svg" alt="">

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
  min-height: 540px;
  margin-bottom: max(150px, 20vh);
}

.section-text {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: justify;
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

.section-image img{
  width: 400px;
  height: auto;
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
  .hero{
    margin-bottom: 300px;
  }
}
@media screen and (max-width: 600px) {
  .section-image img{
    width: 300px;
    height: auto;
}
}

</style>
