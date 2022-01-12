<template>
  <div class="round content-container">
    <article class="n-pad">
      <img
        class="round profile-image n-mar-right grey-border"
        src="@/assets/images/andre-vlok-min.jpg"
        alt="Andre Vlok"
      />
      <div>
        <h3 class="about-heading">About Me</h3>

        <p>
          I am an experienced, skilled & qualified UX/UI Designer & Frontend Web
          Developer. I'm passionate about web innovation. It drives me to create
          strategic customer experiences through which customer objectives &
          expectations are met with business goals.
        </p>

        <p>
          My forte is the working with the frontend of financial technology; but
          am exploring the benefits of blockchain technology, AI, as well as the
          world of DeFi.
        </p>

        <p>
          I've worked on an array of projects involving various companies
          namely, Sanlam, AuctionInc, Monify, King Price, BetterBond and more.
        </p>
        <p>
          I have a high-level of emotional intelligence partnered with a
          perceptive nature, that enables me to understand people, their
          behavior and perspectives. I am a great listener, and acknowledge
          thorough, clear and persuasive communication. My own communication is
          embedded in analytical reasoning and solution-oriented strategic
          thinking. These skills have all been strengthened by my creative
          pursuits namely, playing instruments and creative writing.
        </p>
        <p><b>I look forward to working with you.</b></p>
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
  @include respond(mobitab) {
    margin-bottom: 2rem;
  }
}
article {
  @media screen and (min-width: 1594px) {
    height: 330px;
  }
}
</style>
