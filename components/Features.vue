<template>

  <div class='features'>
    <div class="feature" id='feature1'>
      <img src='../assets/images/logos/Phone.svg' alt='Phone'>
      <h3>Titre H3</h3>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus sed nesciunt cupiditate ex nisi aut ipsam natus esse repudiandae reprehenderit!</p>
      <button class='btn-orange'>Start</button>
    </div>

    <div class="feature" id='feature2'>
      <img src='../assets/images/logos/Code.svg' alt='Phone'>
      <h3>Titre H3</h3>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus sed nesciunt cupiditate ex nisi aut ipsam natus esse repudiandae reprehenderit!</p>
      <button class='btn-orange'>Start</button>
    </div>

    <div class="feature" id='feature3'>
      <img src='../assets/images/logos/Chart.svg' alt='Phone'>
      <h3>Titre H3</h3>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus sed nesciunt cupiditate ex nisi aut ipsam natus esse repudiandae reprehenderit!</p>
      <button class='btn-orange'>Start</button>
    </div>
  </div>

</template>

<script>
export default {};
</script>

<style scoped>

.features{
  display: flex;
  justify-content: space-around;
}

.feature{
  background: #F3F3F3;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 30px;
  box-shadow: 5px -2px 10px rgba(0, 0, 0, 0.25);
  border-radius: 18px;
  width: 300px;
  height: 350px;
  margin: 30px;
}

img{
  height: 50px;
  width: auto;
}

h3{
  margin-top: 30px;
}

p{
  margin-top: 30px;
  width: 260px;
}

button{
  width: 50%;
  margin-right: 115px;
  margin-top: 30px;
}

#feature1{
  margin-top: 0px;
}

#feature2{
  margin-top: 70px;
}

#feature3{
  margin-top: 20px;
}

/* -------------------- Responsive -------------------- */

@media screen and (max-width: 1200px) {
  .features{
    flex-wrap: wrap;
  }
  #feature3{
    margin-top: 40px;
  }
  #feature2{
    margin-top: 40px;
  }
}

</style>
