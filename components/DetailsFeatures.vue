<template>
<div class="detailsFeatures">
  <section>
      <div class="section-image">
        <img src="../assets/images/undraw_profile_image_re_ic2f 1.svg" alt="">
      </div>
      <div class="section-text">
        <h4>Titre h4</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam eu,
          adipiscing congue velit. Nunc diam in id aliquam id massa, nulla. Sed
          malesuada rhoncus ullamcorper auctor mattis sed odio. Vivamus
          condimentum sit varius nisl. Lorem ipsum dolor sit amet, consectetur
          adipiscing elit. Etiam eu, adipiscing congue velit. Nunc diam in id
          aliquam id massa, nulla. Sed malesuada rhoncus ullamcorper auctor
          mattis sed odio. Vivamus condimentum sit varius nisl.
        </p>
        <button class="btn-orange"></button>
      </div>
    </section>

    <section>
       <div class="section-text">
        <h4>Titre h4</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam eu,
          adipiscing congue velit. Nunc diam in id aliquam id massa, nulla. Sed
          malesuada rhoncus ullamcorper auctor mattis sed odio. Vivamus
          condimentum sit varius nisl. Lorem ipsum dolor sit amet, consectetur
          adipiscing elit. Etiam eu, adipiscing congue velit. Nunc diam in id
          aliquam id massa, nulla. Sed malesuada rhoncus ullamcorper auctor
          mattis sed odio. Vivamus condimentum sit varius nisl.
        </p>
        <button class="btn-orange"></button>
      </div>
       <div class="section-image">
        <img src="../assets/images/undraw_profile_image_re_ic2f 1.svg" alt="">
      </div>
    </section>

    <section>
       <div class="section-text">
        <h4>Titre h4</h4>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam eu,
          adipiscing congue velit. Nunc diam in id aliquam id massa, nulla. Sed
          malesuada rhoncus ullamcorper auctor mattis sed odio. Vivamus
          condimentum sit varius nisl. Lorem ipsum dolor sit amet, consectetur
          adipiscing elit. Etiam eu, adipiscing congue velit. Nunc diam in id
          aliquam id massa, nulla. Sed malesuada rhoncus ullamcorper auctor
          mattis sed odio. Vivamus condimentum sit varius nisl.
        </p>
        <button class="btn-orange"></button>
      </div>
       <div class="section-image">
        <img src="../assets/images/undraw_profile_image_re_ic2f 1.svg" alt="">
      </div>
    </section>

</div>
</template>

<script>
export default {};
</script>

<style scoped>

.detailsFeatures {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 10px;  
  position: relative;
  top: 300px;
}

section {
  display: flex;
  text-align: center;
  padding: 5%;
}

h4,
p {
  max-width: 700px;
  color: #f3f3f3;
}

.section-text {
  align-items: center;
  align-self: center;
}

.section-text > p {
  margin: 30px 100px;
  /* align-content: center; */
  text-align: left;
}

.section-image {
  margin: 0 30px 0 0;
}

</style>
