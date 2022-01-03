<template>
  <div>
    <div class="header n-pad">
      <div style="display: inline-flex;">
        <img
          style="margin-left: 1rem; margin-right: 1rem;"
          src="@/assets/logos/vlox-logo.svg"
          alt="VLOX Logo"
        />
        <h3 class="welcomer" style="margin-top: 1.8rem;">
          <span class="underline">Welcome, I'm Andre!</span> 👋
        </h3>
        <img
          class="round"
          style="position: absolute; right: 1rem; top: 2rem; width: 90px; border: .27rem solid #ff4c42;"
          src="@/assets/images/andre-vlok.jpg"
          alt=""
        />
      </div>
      <div class="center n-pad">
        <br />
        <br />
        <h1>I'm a<span class="color-1"> Software Experience Engineer</span></h1>

        <div style="margin: 0 auto; width: 80%;">
          <h2>
            <span class="color-2">I design</span> strategic user experiences,
            that <span class="color-2">I code</span> into high-end scalable
            <span class="color-1">prototypes</span>. Integrated with analytics
            and a CMS, <span class="color-3">you remain in control</span>.
            Delivered through an <span class="color-4">ultra-fast CDN </span>and
            deployed from <span class="color-4">secure repos</span>;
            <i
              >your prototype is the precursor to your production ready
              application.</i
            >
          </h2>
        </div>
        <button class="button-1" id="scrollHandler">
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
    <div class="center"><p>&copy; VLOX 2021</p></div>
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
  @include respond(mobitab) {
    width: 180px;
  }
}
main {
  padding-top: 0 !important;
}
</style>
