<template>
  <div>
    <div class="header n-pad">
      <div class="m-mar-bottom" style="display: inline-flex;">
        <img
          style="margin-left: 1rem; margin-right: 1rem;"
          src="@/assets/logos/vlox-logo.svg"
          alt="VLOX Logo"
        />
        <h3 class="welcomer" style="margin-top: 1.8rem;">
          <span class="underline">Welcome, I'm Andre!</span> 👋
        </h3>
        <img
          class="round profile"
          style="position: absolute; right: 1rem; top: 2rem; width: 90px; border: .27rem solid #ff4c42;"
          src="@/assets/images/andre-vlok-min.jpg"
          alt=""
        />
      </div>
      <div class="center n-pad-bottom">
        <h1>I'm a UX/UI Engineer</h1>

        <div style="margin: 0 auto; width: 72%;">
          <h2>
            <span class="clr-2">I design</span> strategic user experiences, that
            <span class="clr-2">I code</span> <br />
            into <span class="clr-1">scalable</span>,
            <span class="clr-3"> responsive </span>
            <span class="clr-4">prototypes</span>
          </h2>
          <h4>
            These are delivered through an ultra-fast CDN and deployed from
            secure repositories. <br />
            <i
              >Your coded prototype is the foundation to your production ready
              application.</i
            >
          </h4>
        </div>
        <button class="n-mar-top" id="scrollHandler">
          Let's Build Your Ideas!
        </button>
      </div>
      <br />
    </div>
    <br id="scrollHook" />
    <br />
    <main>
      <InfoSections />
    </main>
    <hr />
    <div class="center"><p>&copy; VLOX 2022</p></div>
  </div>
</template>
<script>
import $ from "jquery";
import InfoSections from "../components/Nav.vue";

export default {
  name: "Home",
  components: { InfoSections },
  mounted() {
    $("#scrollHandler").click(function() {
      $("html,body").animate(
        {
          scrollTop: $("#scrollHook").offset().top,
        },
        "fast"
      );
    });
  },
};
</script>
<style lang="scss" scoped>
.header {
  @include respond(lapdesk) {
    height: 100vh;
  }
}
.welcomer {
  @include respond(mobile) {
    width: 150px;
  }
}
.profile {
  @include respond(mobile) {
    width: 70px !important;
    top: 3.5rem !important;
    right: 1.5rem !important;
  }
}
main {
  padding-top: 0 !important;
}
</style>
