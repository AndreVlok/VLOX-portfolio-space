<template>
  <div class="round content-container">
    <!-- AuctionInc -->
    <article class="grid_1-2 n-pad">
      <div
        class="round hide-scroll"
        style="height: 500px; overflow-y: scroll; border: 1px solid #333"
      >
        <perfect-scrollbar>
          <img
            style="width:100% !important;"
            src="@/assets/images/auctioninc-tswhane-page-min.png"
            alt="AuctionInc Tswhane Landing Page"
          />
        </perfect-scrollbar>
      </div>
      <div>
        <img
          height="40"
          src="@/assets/logos/auctioninc-logo-for-light-background.png"
          alt="AunctionInc Logo"
        />

        <h4>Lead-Gen Landing Page</h4>

        <div>
          <p>
            A landing page I developed for AuctionInc. South Africa's largest
            residential property auction house. AuctionInc's marketing objective
            with this landing page is to expand their reach into Tswhane.
          </p>
          <p>
            The page generates leads through a simple web-form that capture the
            customer data and sends it to a Google Sheet, making it easy for
            AuctionInc's team to process the leads.
          </p>
          <a href="https://auctioninc-tswhane.netlify.app/" target="_blank">
            <button>View Project</button>
          </a>
        </div>
      </div>
    </article>

    <!-- Monify & Sanlam -->
    <article class="grid_1-2 n-pad">
      <div
        class="round hide-scroll"
        style="height: 500px; overflow-y: scroll; border: 1px solid #333"
      >
        <perfect-scrollbar class="round">
          <Carousel :autoplay="8000">
            <Slide v-for="sixslide in sixslides" :key="sixslide">
              <img style="width: 100% !important;" :src="sixslide"
            /></Slide>
          </Carousel>
        </perfect-scrollbar>
      </div>
      <div>
        <img
          height="50"
          src="@/assets/logos/monify-logo-for-light-background.svg"
          alt="Monify logo"
        />

        <h4>Sanlam Funeral Cover through Monify</h4>

        <p>
          A design I did for an Extended Family Funeral Cover calculator offered
          by Monify, provided by Sanlam.
        </p>

        <a download href="/sanlam-extended-family-funeral-cover-monify.pdf">
          <button>Download Designs</button>
        </a>
      </div>
    </article>

    <!-- unfolded -->
    <article class="grid_1-2 n-pad">
      <div
        class="round hide-scroll"
        style="height: 500px; overflow-y: scroll; border: 1px solid #333"
      >
        <perfect-scrollbar class="round">
          <img
            style="width:100% !important;"
            src="@/assets/images/unfolded-min.png"
            alt="unfolded"
          />
        </perfect-scrollbar>
      </div>

      <div>
        <img
          height="55"
          src="@/assets/logos/unfolded-logo.svg"
          alt="unfolded logo"
        />

        <h4>A Frontend Framework</h4>

        <p>
          An easy-to-use SCSS framework I built. unfolded develops the design
          for you. Fully responsive with a simple grid system, a few classes for
          powerful tweaking and a beautiful clean look & feel. The perfect
          framework for your next prototype or web app.
        </p>

        <a target="_blank" href="https://unfolded.netlify.app/">
          <button>Check It Out</button>
        </a>
      </div>
    </article>

    <!-- Betterbond Personal Loans -->
    <article class="grid_1-2 n-pad">
      <div
        class="round hide-scroll"
        style="height: 500px; overflow-y: scroll; border: 1px solid #333"
      >
        <perfect-scrollbar class="round">
          <Carousel :autoplay="8000">
            <Slide v-for="slide in slides" :key="slide">
              <img
                class="round"
                style="border: 1px solid #ccc; width:100% !important;"
                :src="slide"
            /></Slide>
          </Carousel>
        </perfect-scrollbar>
      </div>
      <div>
        <img
          height="30"
          src="@/assets/logos/betterbond-logo.svg"
          alt="BetterBond logo"
        />
        <h4>Personal Loans Page</h4>
        <p>
          A design I did for BetterBond's Personal Loans calculator which
          calculates loan amounts, terms & interest rates. Followed by a
          lead-gen form that sends an API call to the loan partners, assessing
          whether the customer qualifies for the requested loan.
        </p>
        <p>
          Upon qualification the customer is presented with loan offers from
          BetterBond's partners, from which the customer can then click-through
          to either receive a call from a call center or be directed to the
          respective loan partners application page.
        </p>

        <a href="/betterbond-personal-loan-offers.pdf" download>
          <button>Download Designs</button>
        </a>
      </div>
    </article>

    <!-- Monify Personal Loans -->
    <article class="grid_1-2 n-pad">
      <div
        class="round hide-scroll"
        style="height: 800px; overflow-y: scroll; border: 1px solid #333"
      >
        <perfect-scrollbar class="round">
          <Carousel :autoplay="8000">
            <Slide v-for="twoslide in twoslides" :key="twoslide">
              <img class="round" style="width: 80% !important;" :src="twoslide"
            /></Slide>
          </Carousel>
        </perfect-scrollbar>
      </div>

      <div>
        <img
          height="50"
          src="@/assets/logos/monify-logo-for-light-background.svg"
          alt="Monify logo"
        />
        <h4>Monify Mobile Personal Loans Process</h4>
        <p>
          A design I did for Monify's (Financial Services for Government
          Employees) Personal Loans SMS sweep (OTP drop-off) campaign; with the
          business objective being to get the customer to subscribe in unison
          with them submitting their personal details for loan qualification.
        </p>
        <p>
          Government employees in Monify's database are sent SMS's to market
          them personal loans. Once they click-through on the link in the SMS,
          the customer lands on a loan calculator page. After playing with the
          calculator the customer clicks on the 'fixed to screen' [GET LOAN NOW]
          button. With the objective being subscribe & apply, the customer is
          presented with a modal-form that functions both as a subscription
          submission and loan qualification (which is run to loan partners
          through an API call on the backend).
        </p>
        <p>
          Upon completion of the form the customer is presented with loan offers
          from Monify's partners, from which the customer can then click-through
          to either receive a call from a call center or be directed to the
          respective loan partners application page. Post submission the
          customer is redirected back to Monify and presented with a post-submit
          modal.
        </p>
        <a download href="/monify-personal-loans.pdf">
          <button>Download Designs</button>
        </a>
      </div>
    </article>

    <!-- Flipit -->
    <article class="grid_1-2 n-pad">
      <div
        class="round hide-scroll"
        style="height: 400px; overflow-y: scroll; border: 1px solid #333"
      >
        <perfect-scrollbar class="round">
          <Carousel :autoplay="8000">
            <Slide v-for="threeslide in threeslides" :key="threeslide">
              <div class="round">
                <img
                  class="round"
                  style="width: 80% !important;"
                  :src="threeslide"
                /></div
            ></Slide>
          </Carousel>
        </perfect-scrollbar>
      </div>
      <div>
        <img
          height="70"
          src="@/assets/logos/flipit-logo.svg"
          alt="Flipit logo"
        />

        <h4>Bitcoin Betting Mobile Web App</h4>

        <p>
          A just-for-fun personal project I designed and developed.
        </p>

        <p>
          The Bitcoin betting application works as follows: The customer bets
          Bitcoin on the outcome of a coin flip determined by the answer of a
          weekly question. In this case the question asks whether the market
          price of Bitcoin will be below or above a certain amount.
        </p>

        <a target="_blank" href="https://flipit2win.netlify.app">
          <button>Play Around</button>
        </a>
      </div>
    </article>

    <!-- PayRun -->
    <article class="grid_1-2 n-pad">
      <div
        class="round hide-scroll"
        style="height: 400px; overflow-y: scroll; border: 1px solid #333"
      >
        <perfect-scrollbar class="round">
          <Carousel :autoplay="8000">
            <Slide v-for="fiveslide in fiveslides" :key="fiveslide">
              <div class="round">
                <img
                  class="round"
                  style="border: 1px solid #ccc; width: 100% !important;"
                  :src="fiveslide"
                /></div
            ></Slide>
          </Carousel>
        </perfect-scrollbar>
      </div>
      <div>
        <img
          height="40"
          src="@/assets/logos/payrun-logo.png"
          alt="PayRun logo"
        />

        <h4>PayRun Internal Payments</h4>

        <p>
          A UI I designed for an internal payment processing solution that
          verify's and initiates payments to customers' eWallets (provided by
          Prepaid24 & SmartFund) embedded on Monify (Financial Services for
          Government Employees) platform.
        </p>

        <a download href="/payrun.pdf">
          <button>Download Design</button>
        </a>
      </div>
    </article>

    <!-- InstaBank -->
    <article class="center n-pad">
      <img
        class="n-mar-top"
        height="70"
        src="@/assets/logos/instabank-logo.svg"
        alt="InstaBank logo"
      />
      <a download href="@/assets/docs/instabank.pdf">
        <h4>InstaBank Brand Identity</h4>
      </a>
      <div class="center" style="max-width: 500px;">
        <p>
          A concept bank brand identity I designed. InstaBank offers personal
          insurance, personal loans and a simple debit card.
        </p>
      </div>
      <Carousel :autoplay="8000">
        <Slide v-for="fourslide in fourslides" :key="fourslide">
          <div class="round">
            <img
              class="round"
              style="border: 1px solid #ccc; width: 100% !important;"
              :src="fourslide"
            /></div
        ></Slide>
        <template #addons>
          <Pagination />
        </template>
      </Carousel>
    </article>

    <!-- Swiftouch 
        <article class="center n-pad ">
          <img
            class="n-mar-top"
            height="50"
            src="@/assets/logos/swiftouch-full-logo.svg"
            alt="Swiftouch logo"
          />
          <h4>Web Components</h4>
          <p>
            Built for immediate customer engagement at the marketing touchpoint
            in the customer journey, distributed as hashtaggable content through
            native marketing. These VUE.js components are published as node
            packages, delivering marketing with lead generation functionality
            through an ultra-fast CDN requiring only 2 lines of codes for
            implementation
          </p>
          <hr />
          <div class="left grid_1-2">
            <div>
              <h4>Article on Home Blog</h4>
              <p>
                ... average age of first-time buyers is now around 34, and that
                would suggest that many, if not most, are planning a lasting
                commitment to a home with enough bedroom, leg room and garden
                space to grow a family, and enough living space for easy,
                at-home entertaining.
              </p>
              <SwiftouchCompAuctionInc />
              <p>
                And this is borne out by the latest report from property data
                company Lightstone, which shows that the average life span of
                home ownership...
              </p>
            </div>
            <div>
              <h4>Example 2 - Home Loans Article</h4>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Similique velit animi laborum. Hic beatae cupiditate suscipit
                aspernatur, nisi dicta debitis.
              </p>
              <p>#Component | wararara</p>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Similique velit animi laborum. Hic beatae cupiditate suscipit
                aspernatur, nisi dicta debitis.
              </p>
            </div>
          </div>
        </article>-->
  </div>
</template>

<script>
// import SwiftouchCompAuctionInc from "./SwiftouchCompAuctionInc.vue";
import "vue3-carousel/dist/carousel.css";
import { Carousel, Slide, Pagination } from "vue3-carousel";
export default {
  components: {
    //SwiftouchCompAuctionInc,
    Carousel,
    Slide,
    Pagination,
  },
  data() {
    return {
      slides: [
        require("@/assets/images/betterbond-loans (1)-min.jpg"),
        require("@/assets/images/betterbond-loans (2)-min.jpg"),
        require("@/assets/images/betterbond-loans (3)-min.jpg"),
        require("@/assets/images/betterbond-loans (4)-min.jpg"),
        require("@/assets/images/betterbond-loans (5)-min.jpg"),
      ],
      twoslides: [
        require("@/assets/images/monify-loans (1)-min.jpg"),
        require("@/assets/images/monify-loans (2)-min.jpg"),
        require("@/assets/images/monify-loans (3)-min.jpg"),
        require("@/assets/images/monify-loans (4)-min.jpg"),
        require("@/assets/images/monify-loans (5)-min.jpg"),
      ],
      threeslides: [
        require("@/assets/images/flipit (1)-min.png"),
        require("@/assets/images/flipit (2)-min.png"),
        require("@/assets/images/flipit (3)-min.png"),
        require("@/assets/images/flipit (4)-min.png"),
        require("@/assets/images/flipit (5)-min.png"),
        require("@/assets/images/flipit (6)-min.png"),
        require("@/assets/images/flipit (7)-min.png"),
        require("@/assets/images/flipit (8)-min.png"),
      ],
      fourslides: [
        require("@/assets/images/InstaBank/instabank (1)-min.jpg"),
        require("@/assets/images/InstaBank/instabank (2)-min.jpg"),
        require("@/assets/images/InstaBank/instabank (3)-min.jpg"),
        require("@/assets/images/InstaBank/instabank (4)-min.jpg"),
        require("@/assets/images/InstaBank/instabank (5)-min.jpg"),
        require("@/assets/images/InstaBank/instabank (6)-min.jpg"),
        require("@/assets/images/InstaBank/instabank (7)-min.jpg"),
        require("@/assets/images/InstaBank/instabank (8)-min.jpg"),
        require("@/assets/images/InstaBank/instabank (9)-min.jpg"),
      ],
      fiveslides: [
        require("@/assets/images/payrun (1)-min.jpg"),
        require("@/assets/images/payrun (2)-min.jpg"),
        require("@/assets/images/payrun (3)-min.jpg"),
        require("@/assets/images/payrun (4)-min.jpg"),
        require("@/assets/images/payrun (5)-min.jpg"),
        require("@/assets/images/payrun (6)-min.jpg"),
        require("@/assets/images/payrun (7)-min.jpg"),
      ],
      sixslides: [
        require("@/assets/images/Sanlam/Sanlam - 1-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 2-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 3-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 4-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 5-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 6-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 7-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 8-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 9-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 10-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 11-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 12-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 13-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 14-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 15-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 16-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 17-min.jpg"),
        require("@/assets/images/Sanlam/Sanlam - 18-min.jpg"),
      ],
    };
  },
};
</script>
<style lang="scss" scoped>
article {
  margin-bottom: 2rem !important;
}

/* Hide scrollbar for Chrome, Safari and Opera */
.hide-scroll::-webkit-scrollbar {
  display: none;
}

/* Hide scrollbar for IE, Edge and Firefox */
.hide-scroll {
  -ms-overflow-style: none; /* IE and Edge */
  scrollbar-width: none; /* Firefox */
}

.ps {
  height: 100%;
  background-color: rgb(241, 241, 241);
}
</style>
