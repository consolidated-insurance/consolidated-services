<template lang="jade">
  header
    .container
      img(src="../assets/logo.png")
</template>

<style lang="scss">
  header {
    z-index: 2;
    position: absolute;
    padding: 15px 0;
  }
  @media screen and (max-width: 560px) {
    img {
      width: 140px;
    }
  }
</style>
