<template>
  <div class="content-container">
    <h3 class="txt-center heading-black">
      <i>Hourly Rate = $30.00</i>
    </h3>
    <div class="grid_1-2" style="margin-bottom: 3rem;">
      <!-- STEP 1 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 50px;" src="@/assets/icons/step-1.svg" />
          <h3><b>STEP 1</b></h3>
        </div>
        <h4>Consultation & Scope</h4>
        <p>
          The first step is to have a consultation (virtually, or in person),
          during which we discuss problems, goals, ideas and content.
        </p>
        <p>
          The consultation fee is $40.00, which falls away once the projected is
          quoted and given the go-ahead in the next step.
        </p>
      </article>

      <!-- STEP 2 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 37px;" src="@/assets/icons/step-2.svg" />
          <h3><b>STEP 2</b></h3>
        </div>
        <h4>Project Plan & Quotes</h4>
        <p>
          After our consultation, I'll plan the project to determine timelines,
          the accompanying quote as well as summarize our consultation to what
          is important and outline the best approach to execute the project.
          This is communicated via email.
        </p>
      </article>

      <!-- STEP 3 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 39px;" src="@/assets/icons/step-3.svg" />
          <h3><b>STEP 3</b></h3>
        </div>
        <h4>User Experience Design</h4>
        <p>
          During the UX design phase, strategies to effectively engage your user
          with your product/service and accompanying business goals are created
          and designed into low-fidelty wireframes.
        </p>
        <p style="margin-bottom: 0 !important;">Strategizing involves:</p>
        <div style="grid-gap: 8px !important;" class="grid_2">
          <div>
            <p><b>Information Architecture</b></p>
            <ul>
              <li>Sitemap</li>
              <li>User-flow</li>
              <li>Content Hierarchy Layouts</li>
            </ul>
          </div>
          <div>
            <p><b>Customer Relationship</b></p>
            <ul>
              <li>Persona Targeting</li>
              <li>Customer Journey Map</li>
              <li>Service Blueprint</li>
            </ul>
          </div>
        </div>
      </article>

      <!-- STEP 4 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 40px;" src="@/assets/icons/step-4.svg" />
          <h3><b>STEP 4</b></h3>
        </div>
        <h4>Prototype Development & Testing</h4>
        <p>
          Once the UX design phase is completed, the development of the
          prototype can begin. During prototype development, a fully functional
          working skeleton of your application is built. Included in the build
          is a CMS (content management system - Storyblok) and user analytics
          software (HotJar), this enables you to update your own content and
          analyze user behavior.
        </p>
      </article>

      <!-- STEP 5 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 45px;" src="@/assets/icons/step-5.svg" />
          <h3><b>STEP 5</b></h3>
        </div>
        <h4>Client Content Updates</h4>
        <p>
          With the prototype built, the content can now be updated by the client
          into the respective sections; this is a good point for the client to
          give feedback and discuss any ideas or changes to the prototype.
        </p>
        <p>
          A CMS guide meeting is scheduled to guide the client on how to update
          content through the CMS.
        </p>
      </article>

      <!-- STEP 6 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 43px;" src="@/assets/icons/step-6.svg" />
          <h3><b>STEP 6</b></h3>
        </div>
        <h4>Digital Design & Backend Development</h4>
        <p>
          Once all content has been updated, your application will be
          transferred to our digital design partner (or a designer off your
          preference) to implement brand identity, and the backend developers to
          hook up the required backend (payment gateways, databases, web forms &
          more).
        </p>
      </article>

      <!-- STEP 7 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 40px;" src="@/assets/icons/step-7.svg" />
          <h3><b>STEP 7</b></h3>
        </div>
        <h4>Staging Testing</h4>
        <p>
          Once all content has been updated and the design and development
          completed, the application is deployed to a staging environment to run
          a test.
        </p>
      </article>

      <!-- STEP 8 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 43px;" src="@/assets/icons/step-8.svg" />
          <h3><b>STEP 8</b></h3>
        </div>
        <h4>Production Launch</h4>
        <p>
          When all is set, and the tests were successful, the application gets
          deployed to a production environment where it will be marketable and
          live to the public.
        </p>
      </article>
    </div>

    <!-- Additional Benefits -->
    <article class="n-pad color-2-border">
      <h4 class="txt-center"><b>Additional Benefits</b></h4>
      <table class="round">
        <tr>
          <td>Minimal Hosting Costs</td>
        </tr>
        <tr>
          <td>Deployment Setup & Administration</td>
        </tr>
        <tr>
          <td>Ongoing Domain Name Implementation & Management</td>
        </tr>
        <tr>
          <td>Ultra Fast Page Delivery via Netlify CDN</td>
        </tr>
        <tr>
          <td>
            Private & Secure Bitbucket & GitHub Code Repositories
          </td>
        </tr>
        <tr>
          <td>
            Environments for development, staging and production
          </td>
        </tr>
        <tr>
          <td>
            Application Usability Testing
          </td>
        </tr>
      </table>
    </article>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
h3 {
  color: $color-1;
  margin: 0.5rem 1.4rem auto 1.4rem;
}

.wrapper {
  display: inline-flex;
}

.heading-black {
  color: #383536 !important;
  margin: 3rem auto;
}
</style>
