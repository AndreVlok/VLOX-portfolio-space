<template>
  <div class="round content-container">
    <article class="n-pad black-border-bottom">
      <img
        class="round profile-image n-mar-right n-mar-bottom"
        src="@/assets/images/andre-vlok-min.jpg"
        alt="Andre Vlok"
      />
      <div>
        <h3 class="about-heading">About Me</h3>
        <p>
          I am a creative; passionate about customer-centric web innovation. It
          drives me to design strategic customer experiences through which
          customers are benefitted by business goals.
        </p>
        <p>
          My <i>forte</i> is the working with the frontend of financial
          technology; but am exploring the benefits of blockchain technology,
          AI, as well as the world of DeFi.
        </p>
        <p>
          I've worked on an array of projects involving various companies,
          namely: Sanlam, AuctionInc, Monify, King Price, BetterBond and more.
        </p>
        <p>I look forward to working with you.</p>
      </div>
    </article>
  </div>
</template>
<script>
export default {};
</script>
<style scoped lang="scss">
.about-heading {
  margin: auto auto 0 auto;
}
.profile-image {
  float: left;
  max-width: 320px;
  width: 100%;
}
article {
  @media screen and (min-width: 1594px) {
    height: 330px;
  }
}
</style>
