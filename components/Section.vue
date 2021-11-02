<template>
  <div>
    <div class="background">
    <Features />
    <DetailsFeatures />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.background {
  background-color: var(--grey);
  height: auto;
  padding-bottom: 500px;
}

@media screen and (max-width: 1200px) {
  .background {
    padding-bottom: 1000px;
  }
}
@media screen and (max-width: 839px) {
  .background {
    padding-bottom: 1400px;
  }
}

</style>
