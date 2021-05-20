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
  display: flex;
  text-align: center;
  padding: 10px;
}

.section-text {
  flex: auto;
  justify-content: center;
  align-items: center;
  align-self: center;
}

.section-text > p {
  margin: 30px 100px;
  align-content: center;
  text-align: left;
}

.section-image {
  margin: 0 30px 0 0;
}

</style>
