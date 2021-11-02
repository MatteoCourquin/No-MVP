<template>
  <div class='footer'>

    <div class='contenu'>
      <div class='titre'>
        <img class="logo" src="../assets/images/logos/NoMVP_Black.png" alt="logo"/>
        <h5>Titre H5</h5>
      </div>

      <p class='texte'>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque repellendus tempora ab velit at ex non ut reiciendis maiores, laboriosam cumque optio molestiae veniam nam voluptatem aliquid mollitia quisquam vel! Lorem ipsum, dolor sit amet consectetur adipisicing elit. Et reprehenderit possimus quidem commodi ducimus. Quae saepe earum quaerat error esse debitis, vel excepturi quidem, ipsa labore molestiae quo. Labore, iusto?</p>

      <button class='btn-black'>CONTACT</button>
    </div>

    <div class='navlink'>
      <NuxtLink class="nav-link" to="#">nav-link</NuxtLink>
      <NuxtLink class="nav-link" to="#">nav-link</NuxtLink>
      <NuxtLink class="nav-link" to="#">nav-link</NuxtLink>
      <NuxtLink class="nav-link" to="#">nav-link</NuxtLink>
    </div>

    <div class="footerSocialMedia-Copiright">
      <div>
        <p class='copyright'>© Copyright No-MVP {{  today  }} •</p>
      </div>

      <div class='socialmedias'>
        <i class="fab fa-facebook"></i>
        <i class="fab fa-twitter"></i>
        <i class="fab fa-instagram"></i>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  
  data(){
    return {
      today: 2021
    }
  },

};
</script>

<style scoped>

.footer{
  background: linear-gradient(177deg, #FFAE4F 0%, #DB873D 95.15%);
  box-shadow: 5.88605px 112.313px 224.933px rgba(51, 31, 14, 0.2085), inset -1.71349px -32.6954px 32.7403px #D2813A, inset 1.71349px 32.6954px 32.  7403px #FFB351;
  border-radius: 40px;
  z-index: 1;
  display: grid;
  grid-template-columns: 50% 50%;
  grid-template-rows: 1fr;
  width: 80%;
  margin: 0% 10%;
  margin-bottom: 50px;
  margin-top: -100px;
}

.titre{
  display: flex;
}

h5{
  font-size: 50px;
  margin-left: 20%;
  align-self: center;
}

.logo{
  width: 120px;
}

.contenu{
  margin: 40px;
}

.texte{
  margin: 55px 0px;
  text-align: justify;
}

.btn-black{
  width: 250px;
  height:50px;
  font-size: 20px;
}

.nav-link{
  color: var(--white);
  text-decoration: none;
}

.navlink{
  margin: 30px;
  display: grid;
  grid-template-columns: 150px 100px;
  grid-template-rows: 40px 40px ;
  justify-content: center;
  align-self: center;
}

.copyright{
  color: var(--white);
}

.footerSocialMedia-Copiright{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  margin-bottom: 30px;
  grid-column: 1 / 3;
}

i{
  margin: 15px;
  font-size: 30px;
}

@media screen and (max-width: 800px) {
  .footer{
    display: flex;
    flex-direction: column;
  }
}
@media screen and (max-width: 600px) {
  .footer{
    border-radius: 0px;
    width: 100%;
    margin: 0;
    margin-bottom: 0px;
    margin-top: -100px;
  }
}
@media screen and (max-width: 500px) {
  .footerSocialMedia-Copiright{
    display: flex;
    flex-direction: column-reverse;
    align-items: center;
    margin-bottom: 30px;
  }
  .socialmedias{
    margin-bottom: 20px;
  }
}

</style>
