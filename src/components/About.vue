<template>
  <div class="round content-container">
    <div class="n-pad">
      <img
        class="round profile-image n-mar-right brdr-black"
        src="@/assets/images/andre-vlok-min.jpg"
        alt="Andre Vlok"
      />
      <div>
        <h3 class="about-heading">About Me</h3>

        <p>
          I am an experienced, skilled & qualified User Experience Engineer. I'm
          passionate about internet innovation. I create strategic customer
          experiences that aligns customer objectives with business goals.
        </p>

        <p>
          My <i>forte</i> is the working with the front-end of financial
          technology; but I am developing a lot of exciting new interest in the
          benefits of DeFi, dApps & blockchain as a whole.
        </p>

        <p>
          I've worked on an array of projects involving various blue chip
          companies like Sanlam, BetterBond, DirectAxis, AuctionInc, Monify,
          King Price, and others.
        </p>
        <p>
          I have over 5 years experience as a UX/UI Designer working on Adobe
          Creative Cloud apps. And 3+ years’ experience developing web
          applications with HTML, CSS/SCSS, JavaScript, VUE.js & jQuery. I
          consider myself an experienced UX/UI designer, a skilled JavaScript
          developer and an expert in HTML & CSS/SCSS.
        </p>
        <p>
          I have a high-level of emotional intelligence partnered with a
          perceptive nature, that enables me to understand people, their
          behaviour and perspectives. I am a great listener, and value thorough
          and transparent communication. My own communication conveys my skills
          to reason analytically and to notice opportunities. These attributes
          have all been strengthened by my creative pursuits which include,
          playing instruments, singing, and creative writing.
        </p>
        <p><b>I look forward to connecting and working with you.</b></p>
      </div>
    </div>
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
