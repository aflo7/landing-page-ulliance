<script setup></script>

<template>
  <nav>
    <img
      src="https://ulliance.com/wp-content/uploads/2020/11/Ulliance-Logo-Tagline.png"
      class="ulliance-logo"
    />
    <div class="bottom-nav">
      <div>Get Help</div>
      <div>EAP Login</div>
      <div>Well-being Login</div>
    </div>
  </nav>

  <div
    style="
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 30px;
      align-items: center;
    "
  >
    <div class="hidden">Services</div>
    <div class="hidden">EAP Resources</div>
    <div class="hidden">Resources</div>
    <div class="hidden">HR Professional</div>
    <div class="hidden">Broker</div>
    <div class="hidden">About Us</div>
    <div class="hidden">Blog</div>
    <button id="menuBtn">Menu</button>
    <button id="getAQuoteBtn">Get A Quote</button>
  </div>
  <main>
    <div class="inner-main">
      <div
        class="inner-main-wrapper"
        style="background-color: rgb(207, 89, 40); color: white"
      >
        <div class="runText" style="font-size: 2rem">
          Run a Healthier Organization With A Better EAP.
        </div>
        <button type="text" id="contactSales">Contact Sales</button>
      </div>
    </div>
  </main>
  <div class="main-inner">
    <p class="orange-text uppercase">What We Do</p>
    <h2 style="font-size: 2.5rem">Enhance People & Improve Business</h2>
    <p>
      Ulliance Life Advisor Well-being addresses the most preventable and most
      costly well-being conditions by leveraging the combination of digital
      tools and resources, one-on-one counseling and expert well-being coaching.
    </p>
    <p>
      We help keep employees focused and productive with programs built on 30+
      years of experience addressing real-life problems.
    </p>
    <img
      src="https://ulliance.com/wp-content/uploads/2022/11/30-wEBSITE-cREST-1.jpg"
      width="160px"
    />
    <p class="orange-text">
      Life can be tough, getting help for your employees is easy with the
      Ulliance Life Advisor EAP.
    </p>
    <p class="orange-text clickText">
      Click the video below to discover how it works
    </p>
  </div>
</template>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
  flex-direction: column;
  align-items: center;
}

.ulliance-logo {
  height: 60px;
  margin: 10px;
}

.uppercase {
  text-transform: uppercase;
}

.bottom-nav {
  display: flex;
  gap: 10px;
  background-color: rgb(239, 228, 208);
  justify-content: center;
  align-items: center;
  width: 100%;
}

.bottom-nav > div {
  cursor: pointer;
  padding: 10px;
}

.bottom-nav > div:hover {
  cursor: pointer;
  color: rgb(207, 89, 40);
}

#menuBtn {
  padding: 10px 20px;
  cursor: pointer;
  color: rgb(207, 89, 40);
  background-color: transparent;
  border: none;
}

#getAQuoteBtn {
  padding: 10px 20px;
  cursor: pointer;
  background-color: rgb(207, 89, 40);
  color: white;
  border: none;
  border: 2px solid rgb(207, 89, 40);
}

#getAQuoteBtn:hover {
  background-color: white;
  color: rgb(207, 89, 40);
  border: 2px solid rgb(207, 89, 40);
}

main {
  background-image: url(https://ulliance.com/wp-content/uploads/2019/04/iStock-593322436_edit_sm.jpg);
  background-image: url(https://ulliance.com/wp-content/uploads/2021/03/Copy-of-How-to-Enhance-Workplace-Diversity-Equity-Inclusion-1.png);
  height: 600px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
}

#contactSales {
  padding: 10px 20px;
  border: 2px solid white;
  background-color: transparent;
  color: white;
  cursor: pointer;
  width: fit-content;
}

#contactSales:hover {
  background-color: white;
  color: rgb(207, 89, 40);
}

.inner-main-wrapper {
  padding: 20px 50px;
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.clickText {
  text-transform: uppercase;
  font-weight: bold;
}

.orange-text {
  color: rgb(207, 89, 40);
}

.inner-main-wrapper {
  background: #555;
}

.main-inner {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px 50px;
  text-align: center;
  max-width: 800px;
  margin: 0 auto;
}

#menuBtn {
  display: block;
}

.hidden {
  display: none;
}

@media only screen and (min-width: 1000px) {
  nav {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }

  #menuBtn {
    display: none;
  }

  .hidden {
    display: block;
  }

  .bottom-nav {
    width: fit-content;
    height: 100%;
  }

  .bottom-nav > div {
    cursor: pointer;
    padding: 30px;
  }

  .ulliance-logo {
    padding-left: 30px;
    margin: 0px;
  }

  .inner-main-wrapper {
    width: 450px;
    align-items: center;
  }

  main {
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }
  .inner-main {
    width: 1000px;
  }

  #contactSales,
  .runText {
    transform: skew(10deg);
  }

  .inner-main-wrapper {
    transform: skew(-10deg);
  }
}
</style>
