<template lang="jade">
  section.media-boxes
    h3 What our customers have to say...
    .row
      .three.column
        img(src="../assets/stock-couple.jpg", class="img-responsive")
      .nine.columns
        p Being a stock photo model couple is a tough career. Doesn't make much money and we're never sure about our next gig. But with Consolidated Insurance Services, we know our convertible will be well protected. Which is why I make Jamie sit in the backseat.
          br
          i Jim and Jamie - Customers since 2015
    .row
      .three.columns
        img(src="../assets/jason-g.jpg", class="img-responsive")
      .nine.columns
        p After winning my fantasy football league I knew I had to start thinking about protecting the loved ones who depend on me. Once I talked with a representive, I knew my cat would be well taken care of if anything were to happen to me.
          br
          i Jason G - Customer since 2007
    .row
      .three.columns
        img(src="../assets/freddy-d.jpg", class="img-responsive")
      .nine.columns
        p Consolidated Insurance Services is being recongnized more and more for their fabulous customer service. I feel like I'm learning something new about them everyday - and it makes me proud to be one of their customers.
          br
          i Freddy D - Customer since 1850

</template>

<style lang="scss" scoped>

  .media-boxes {
    margin-top: 30px;
  }
  .img-responsive {
    width: 100%;
    height: auto;
  }
  blockquote {
    margin: .5rem;
    margin-bottom: 3rem;
  }
  @media screen and (max-width: 560px) {
    .media-boxes {
      text-align: center;
      img {
        max-width:250px;
      }
    }
    h3 {
      font-size: 2rem;
    }
  }

</style>
