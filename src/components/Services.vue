<template>
  <div class="content-container">
    <div class="grid_1-2" style="margin-bottom: 3rem;">
      <!-- STEP 1 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 50px;" src="@/assets/icons/step-1.svg" />
          <h3><b>STEP 1</b></h3>
        </div>
        <h4>Consultation & Scope</h4>
        <p>
          The first step is having a consultation (virtually, or in person),
          during which we discuss problems, goals, ideas and content.
        </p>
        <p>
          The consultation fee is $40.00, which falls away once the project is
          quoted and given the go-ahead in the next step.
        </p>
      </article>

      <!-- STEP 2 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 37px;" src="@/assets/icons/step-2.svg" />
          <h3><b>STEP 2</b></h3>
        </div>
        <h4>Project Roadmap & Quote</h4>
        <p>
          After our consultation, I'll plan the project to determine timelines,
          the accompanying quote as well as outline the best approach to execute
          the project.
        </p>
        <p>
          In addition, I will request the required content from you (the client)
          for the project.
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
          With the legwork completed, the UX design phase can begin. During this
          phase strategies to effectively engage your user, meet their
          expectations, and guide them to accomplish their objectives in an
          intuitive and appealing flow is designed. The end-goal being to marry
          user goals with business goals.
        </p>
        <p style="margin-bottom: 0 !important;">Design Process:</p>
        <div style="grid-gap: 8px !important;" class="grid_2">
          <div>
            <p><b>Information Architecture</b></p>
            <ul>
              <li>Sitemap</li>
              <li>User Flow Mapping</li>
              <li>Content Hierarchy Model</li>
              <li>Low-Fidelty Wireframing</li>
            </ul>
          </div>
          <div>
            <p><b>Customer/Business Relationship</b></p>
            <ul>
              <li>Persona Targeting</li>
              <li>Customer Journey Mapping</li>
              <li>Service Blueprinting</li>
            </ul>
          </div>
        </div>
      </article>

      <!-- STEP 5 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 40px;" src="@/assets/icons/step-4.svg" />
          <h3><b>STEP 5</b></h3>
        </div>
        <h4>Prototype Development & Testing</h4>
        <p>
          After the UX design phase is completed, the project is sent to you for
          review. Once reviewed and changes have been applied, the development
          (coding) of the prototype can begin.
        </p>
        <p>
          During prototype development, a fully functional high-fidelity working
          skeleton of your application is built in
          <a target="_blank" href="https://www.vuejs.org"
            ><span class="clr-2">Vue.js</span></a
          >
          (a progressive JavaScript framework for scalable web apps) and
          <a target="_blank" href="https://www.unfolded.netlify.app"
            ><span class="clr-2">unfolded</span></a
          >
          (a styling framework for web apps).
        </p>
        <p>
          Integrated into the build is user analytics software (<a
            target="_blank"
            href="http://www.hotjar.com"
            ><span class="clr-2">www.hotjar.com </span></a
          >), in order to measure user behavior.
        </p>
        <p>
          After development, an internal test is run to measure usability.
        </p>
      </article>

      <!-- STEP 6 -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 40px;" src="@/assets/icons/step-7.svg" />
          <h3><b>STEP 6</b></h3>
        </div>
        <h4>Handover Launch</h4>
        <p>
          With all the above steps completed, the prototype code is pushed to a
          private & secure
          <a target="_blank" href="https://www.github.com"
            ><span class="clr-2">GitHub</span></a
          >
          repository, from which it gets deployed onto a content delivery
          network (<a target="_blank" href="https://www.netlify.com"
            ><span class="clr-2">www.netlify.com</span></a
          >) into a development environment. This enables your design &
          development team to access the source code & review the prototype on
          the internet.
        </p>
        <p>
          A final handover presentation (virtually, or in person) is done with
          you and respective teams, during which a link to the project
          documentation and prototype is shared.
        </p>
      </article>

      <!-- NEXT STEPS -->
      <article class="n-pad">
        <div class="wrapper">
          <img style="width: 43px;" src="@/assets/icons/step-6.svg" />
          <h3><b>NEXT STEPS</b></h3>
        </div>
        <h4>Digital Design & Backend Development</h4>
        <p>
          With the prototype complete, your design & development teams can now
          access/download the source code to implement brand identity and other
          design elements as well as further develop backend functionality to
          convert the prototype into a production ready application.
        </p>
      </article>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
article {
  border-left: 2px solid $clr-2;
  border-top: 2px solid $clr-2;
}
h3 {
  color: $clr-1;
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
