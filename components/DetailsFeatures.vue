<template>
<div class="detailsFeatures">
  <section>
      <div class="section-image">
        <img src="../assets/images/logoPhone.svg" alt="illustration d'un telephone portable">
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
        <img src="../assets/images/logoChat.svg" alt="illustration de chat en ligne">
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
        <img src="../assets/images/logoCalendar.svg" alt="illustration de calendrier">
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
  text-align: justify;
}

section:nth-child(3){
  flex-direction: column;
}

.section-image {
  margin: 0 30px 0 0;
  display: flex;
  align-items: center;
  justify-content: center;
}

.section-image img{
  height: 300px;
  width: auto;
}

@media screen and (max-width: 1200px) {
    .detailsFeatures{
      top: 800px;
    }
    .section-image img{
      height: 150px;
      width: auto;
      margin-top: 20px;
    }
}
@media screen and (max-width: 839px) {
    .detailsFeatures{
      top: 1200px;
    }
    section{
      flex-direction: column;
    } 
    section:nth-child(1){
      flex-direction: column-reverse;
    }
    .section-text > p {
      margin: 30px 20px;
    }
    .section-text {
      margin: 50px 0;
    }
}

</style>
