<template>
  <div class="wrap">
    <Pointer />
    <div class="hero-manifesto">
      <div class="heading-wrapper">
        <div class="wrap-head">
          <div>
            <h1 class="heading">Contact Us</h1>
          </div>
          <h1 class="shadow-heading">CONTACT</h1>
          <p style="padding-bottom: 3rem" class="paragraph-hero">
            We’d love to hear from you
          </p>
        </div>
      </div>
    </div>
    <div class="smooth-scroll-fix">
      <main>
        <section class="contained">
          <div id="contact_container" class="contained">
            <div class="contact_section card">
              <div>
                <h2>Submit an idea</h2>
                <p>
                  If you have an idea or solution that you would like to share
                  with us, please get in touch
                </p>
                <nuxt-link to="/form"
                  ><span
                    @mouseover="active22 = true"
                    @mouseleave="active22 = false"
                    >Submit idea</span
                  ></nuxt-link
                >
              </div>
              <div class="lottie">
                <lottie-player
                  id="firstLottie"
                  :class="{ hide: active22 }"
                  class="lot"
                  style="width: 100px"
                  src="https://assets7.lottiefiles.com/packages/lf20_mypsaacn.json"
                ></lottie-player>
                <lottie-player
                  id="secondLottie"
                  class="lot"
                  :class="{ show: active22 }"
                  loop
                  autoplay
                  style="width: 100px"
                  hover
                  src="https://assets7.lottiefiles.com/packages/lf20_mypsaacn.json"
                ></lottie-player>
              </div>
            </div>

            <div class="contact_section card">
              <div>
                <h2>Email us</h2>
                <p>Anything else to ask the team?</p>
                <a
                  href="mailto:innovation@boots.co.uk"
                  @mouseover="active1 = true"
                  @mouseleave="active1 = false"
                  >Send Email</a
                >
              </div>
              <div class="lottie">
                <lottie-player
                  id="firstLottie"
                  :class="{ hide: active1 }"
                  class="lot"
                  style="width: 100px"
                  src="https://assets5.lottiefiles.com/packages/lf20_wp8xrxjo.json"
                ></lottie-player>
                <lottie-player
                  id="secondLottie"
                  :class="{ show: active1 }"
                  class="lot"
                  loop
                  autoplay
                  style="width: 100px"
                  hover
                  src="https://assets5.lottiefiles.com/packages/lf20_wp8xrxjo.json"
                ></lottie-player>
              </div>
            </div>

            <div class="contact_section card">
              <div>
                <h2>Visit us</h2>
                <p>We’re based in the UK</p>
                <a
                  href="https://goo.gl/maps/YPAsGjyZTJutzT2r6"
                  target="blank_"
                  @mouseover="active3 = true"
                  @mouseleave="active3 = false"
                  >See Location</a
                >
              </div>
              <div class="lottie">
                <lottie-player
                  id="firstLottie"
                  :class="{ hide: active3 }"
                  class="lot"
                  style="width: 100px"
                  src="https://assets2.lottiefiles.com/packages/lf20_uhj0vach.json"
                ></lottie-player>
                <lottie-player
                  id="secondLottie"
                  :class="{ show: active3 }"
                  class="lot"
                  style="width: 100px"
                  loop
                  autoplay
                  src="https://assets2.lottiefiles.com/packages/lf20_uhj0vach.json"
                ></lottie-player>
              </div>
            </div>

            <div class="contact_section card">
              <div>
                <h2>Join us</h2>
                <p>Looking for a career at Boots?</p>
                <a
                  href="https://www.boots.jobs/"
                  target="blank_"
                  @mouseover="active4 = true"
                  @mouseleave="active4 = false"
                  >See Careers</a
                >
              </div>
              <div class="lottie">
                <lottie-player
                  id="firstLottie"
                  :class="{ hide: active4 }"
                  class="lot"
                  style="width: 100px"
                  src="https://assets3.lottiefiles.com/packages/lf20_c5x66li9.json"
                ></lottie-player>
                <lottie-player
                  id="secondLottie"
                  :class="{ show: active4 }"
                  class="lot"
                  loop
                  autoplay
                  style="width: 100px"
                  src="https://assets3.lottiefiles.com/packages/lf20_c5x66li9.json"
                ></lottie-player>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>
  </div>
</template>
<script>
import '@lottiefiles/lottie-player'
require('@lottiefiles/lottie-player')

export default {
  data() {
    return {
      active1: false,
      active22: false,
      active3: false,
      active4: false,
    }
  },
}
</script>

<style scoped>
.hero-manifesto {
  padding-top: 8rem;
  color: #20325a;
  background-color: white;
}
.heading-wrapper {
  display: grid;
  position: relative;
  text-align: center;
  gap: 3rem;
  justify-content: center;
}

.shadow-heading {
  display: grid;
  justify-content: center;
  font-size: 6rem;
  font-weight: 800;
  color: #7f889613;
}
.heading {
  margin-left: 10rem;
  margin-top: 2.7rem;
  font-weight: bold;
  text-align: center;
  font-size: 2rem;
  color: #323335;
  position: absolute;
}
.wrap-head {
  display: grid;
  justify-content: center;
}
.paragraph-hero {
  max-width: 50ch;
}
.lottie {
  right: 1rem;
}
.wrap {
  background-color: #dfebf8;
}
@media screen and (max-width: 1024px) {
  .smooth-scroll-fix {
    position: relative;
    z-index: 5;
    pointer-events: all;
  }
}
@media (min-width: 768px) {
  .contact_section {
    min-width: 48% !important;
    max-width: 48% !important;
  }
}
a {
  cursor: pointer;
  position: absolute;
  bottom: 1rem;
}
section {
  padding: 2rem;
}
h2 {
  font-size: 1.4rem;
  font-weight: 600;
}
h1 {
  font-size: 1.8rem;
}
.contact_section p {
  color: #666666;
}
.contained {
  max-width: 1280px;
  margin: 0 auto;
}
.contact_section {
  display: block;
  text-align: left;
  min-width: 100%;
  margin: 10px 0;
  flex: 1 1 0px;
  border-bottom: 1px dotted #e5e5e5;
}
#contact_container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.d-flex {
  display: flex;
  flex-direction: row;
  gap: 2rem;
}
h5 {
  padding: 0 !important;
  font-size: 1.2rem;
}

.card p {
  padding-right: 3rem;
  max-width: 40ch;
  padding-bottom: 3rem;
}
.card {
  display: flex;
  gap: 1rem;
  position: relative;
  background-color: #ffffff;
  width: 600px;
  padding: 2rem;
  box-shadow: 0px 3px 6px #00000029;
  border-radius: 6px;
}
p {
  padding-bottom: 1rem;
}
.pb-3 {
  padding-bottom: 2rem;
}
section {
  background-color: #dfe9f2;
}
a {
  background-color: #3d619b;
  padding: 0.5rem 0.8rem 0.5rem 0.8rem;
  color: white;
  box-shadow: 0px 3px 6px #00000029;
  border-radius: 17px;
}
.lot {
  position: absolute;
  right: 1rem;
  top: 0;
}
.show {
  display: block !important;
  transition: 1s;
}
.hide {
  display: none;
  transition: 1s;
}
#secondLottie {
  display: none;
}
</style>
