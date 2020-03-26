<template lang="jade">
  section.cover
    .box
      .well
        h2 We care about your family,
        h2 so you don't have to.
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.cover {
  background: url('../assets/family-home.jpg') no-repeat;
  background-size: cover;
  height: 500px;
  position: relative;
  top: 0;
  left: 0;
  width: 100%;
  .box {
    width: 24rem;
    background: #eeeeee;
    border: 5px solid #0c5296;
    top: 40%;
    left: 20%;
    position: relative;
  }
  .well {
    padding: 15px;
  }
  h2 {
    font-size: 2rem;
    margin: 0;
    color: #2267AA;
  }

}

@media screen and (max-width: 560px) {
  .cover {
    height:300px;
    .box {
      width: 90%;
      left: 5%;
      h2 {
        font-size: 1.5rem;
        text-align: center;
      }
    }
  }
}
</style>
