<template>
  <div>
    <LocomotiveScroll
      id="js-scroll"
      :getted-options="{
        smooth: true,
        getSpeed: true,
        lerp: 0.075,
        smartphone: {
          smooth: true,
        },
        tablet: {
          smooth: true,
        },
      }"
    >
      <Pointer />
      <div style="position: relative; overflow: hidden">
        <Hero :heading="page.heading" :subheading="page.subheading" />
        <Shapes />
      </div>

      <div
        style="display: flex; gap: 8rem"
        class="wrap px-8 mx-auto mt-12 sm:px-6 md:px-4 lg:px-2 xl:px-0 xl:prose-xl lg:prose-lg md:prose-md pb-12"
      >
        <div class="col12 col-m5 col-l5 col-push-m8">
          <div class="half --img" data-effect="fadeUp" data-delay="2">
            <picture
              ><img
                src="https://images.rawpixel.com/image_1300/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvay1zNDYtYWtlLTM5NDcuanBn.jpg"
                alt="Why choose us?"
            /></picture>
          </div>
        </div>
        <div style="max-width: 45ch">
          <h3>
            {{ page.mainpitch.title }}
          </h3>
          <p>
            {{ page.mainpitch.description }}
          </p>
          <p>
            {{ page.mainpitch.description2 }}
          </p>
        </div>
        <!-- <h2>
        {{ page.title }}
      </h2> -->
        <!-- <p>
        {{ page.description }}
      </p> -->
        <!-- <div style="padding-top: 2rem !important">
        <p class="">
          {{ page.description2 }}
        </p>
      </div> -->

        <!-- <div class="lg:grid lg:grid-cols-2 lg:gap-8">
        <div
          v-for="(blurb, index) in page.intro.blurbs"
          :key="index"
          class="flex flex-col items-center px-6 border rounded-lg shadow justify-top"
        >
          <img class="h-32" :src="blurb.image" />
          <p class="mt-2 text-justify">{{ blurb.text }}.</p>
        </div>
      </div> -->
        <!-- <p class="text-center">
        <nuxt-link
          to="/products"
          class="inline-flex items-center px-6 py-3 text-base font-medium leading-6 transition duration-150 ease-in-out bg-white border border-gray-300 rounded-md text-kaldi hover:text-orange-500 focus:outline-none focus:border-blue-300 focus:shadow-outline-blue active:text-gray-800 active:bg-gray-50"
        >
          See all products
        </nuxt-link>
      </p>
      <h2>Latest stories</h2>
      <div class="lg:grid lg:grid-cols-2 lg:gap-8">
        <div
          v-for="(post, index) in posts"
          :key="index"
          class="px-6 border rounded-lg shadow"
        >
          <h3>
            <nuxt-link :to="`/blog/${post.slug}`">{{ post.title }}</nuxt-link>
          </h3>
          <p>
            {{ post.description }}
          </p>
          <p>
            <nuxt-link :to="`/blog/${post.slug}`">Read more</nuxt-link>
          </p>
        </div>
      </div>
      <p class="text-center">
        <nuxt-link
          to="/blog"
          class="inline-flex items-center px-6 py-3 text-base font-medium leading-6 transition duration-150 ease-in-out bg-white border border-gray-300 rounded-md text-kaldi hover:text-orange-500 focus:outline-none focus:border-blue-300 focus:shadow-outline-blue active:text-gray-800 active:bg-gray-50"
        >
          Read more
        </nuxt-link>
      </p> -->
      </div>
      <div class="approach-wrap --offPurple pt-2 pb-12">
        <div
          class="wrap px-8 mx-auto mt-12 sm:px-6 md:px-4 lg:px-2 xl:px-0 xl:prose-xl lg:prose-lg md:prose-md"
        >
          <h3>Approach</h3>
          <p style="max-width: 80ch">
            As part of this sponsorship arrangement TCS will be named Boots’
            Innovation Partner of Choice: Boots and TCS will continue to define
            what this means in more detail, but TCS would largely drive this,
            including:
          </p>
          <div class="cards">
            <div class="card rounded-lg shadow-lg bg-white max-w-sm px-8 py-8">
              <img src="/img/sponsorship.png" alt="" />
              <h4>Executive sponsorship</h4>
              <p>
                From Boots CIO, Richard Corbridge and Transformation Director,
                David Hobbs
              </p>
            </div>
            <div class="card rounded-lg shadow-lg bg-white max-w-sm px-8 py-8">
              <img src="/img/commitment.png" alt="" />
              <h4>Commitment</h4>
              <p>
                Boots commitment to work with TCS Innovation team to develop
                proofs of concept and early prototypes for Boots
              </p>
            </div>
            <div class="card rounded-lg shadow-lg bg-white max-w-sm px-8 py-8">
              <img src="/img/events.png" alt="" />
              <h4>Innovation events</h4>
              <p>Monthly/quarterly innovation events/workshops</p>
            </div>
            <div class="card rounded-lg shadow-lg bg-white max-w-sm px-8 py-8">
              <img src="/img/marketing.png" alt="" />
              <h4>Marketing</h4>
              <p>
                Joint marketing on completion of relevant milestones (service
                launch, POC launch, events, etc)
              </p>
            </div>
            <div class="card rounded-lg shadow-lg bg-white max-w-sm px-8 py-8">
              <img src="/img/coinnovation.png" alt="" />
              <h4>Co-Innovation</h4>
              <p>
                TCS brings different start-ups/universities to come to the space
                and showcase different research/ideas
              </p>
            </div>
            <div class="card rounded-lg shadow-lg bg-white max-w-sm px-8 py-8">
              <img src="/img/showcasing.png" alt="" />
              <h4>Showcasing</h4>
              <p>
                TCS ‘showcase’ zone/screen as part of the area where TCS (or
                partner) solutions/case studies can be shown for the awareness
                of Boots business and IT colleagues
              </p>
            </div>
          </div>
        </div>
        <div class="rightSymbol2 symbol --pink --blur">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="currentColor"
            class="full"
            viewBox="0 0 531 595"
          >
            <use xlink:href="#cSymbol"></use>
          </svg>
        </div>
      </div>
      <div class="wrap mx-auto mt-12 xl:prose-xl lg:prose-lg md:prose-md">
        <h3>About</h3>
        <ul class="projects__list">
          <!--[-->
          <li class="project projects__list__item is-inview">
            <a
              href="https://www.tcs.com/pace"
              target="blank_"
              class="project__wrapper hoverable"
              style="transform: translate(0px, 0px)"
              ><div class="project__image__wrapper">
                <img
                  src="/img/pace.png"
                  alt="LPNU StudRecruit"
                  class="project__image"
                  style="
                    opacity: 1;
                    transform-origin: 50% 100%;
                    transform: translate(0px, 0px);
                  "
                />
              </div>
              <div class="project__content">
                <h3 class="project__content__title">TCS PACE</h3>
              </div></a
            ><!---->
          </li>
          <li
            data-scroll
            :data-scroll-speed="id % 2 === 0 ? -0.5 : 1"
            style="margin-top: 6rem"
            class="project projects__list__item is-inview"
          >
            <a
              href="https://www.boots-uk.com/about-boots-uk/about-boots/"
              target="blank_"
              class="project__wrapper hoverable"
              style="transform: translate(0px, 0px)"
              ><div class="project__image__wrapper">
                <img
                  src="/img/boots.png"
                  alt="Portfolio"
                  class="project__image"
                  style="
                    opacity: 1;
                    transform-origin: 50% 100%;
                    transform: translate(0px, 0px);
                  "
                />
              </div>
              <div class="project__content">
                <h3 class="project__content__title">Boots</h3>
              </div></a
            >
          </li>
          <!--]-->
        </ul>
      </div>
      <div
        style="position: relative; overflow: hidden"
        :class="{ hovered: active3 }"
        class="wrap-idea py-5 px-8 mx-auto mt-12 sm:px-6 md:px-4 lg:px-2 xl:px-0 xl:prose-xl lg:prose-lg md:prose-md pb-12"
      >
        <Shapesidea />
        <h3>Got an idea for us?</h3>
        <p>We would love to hear from you…</p>
        <div style="position: relative" class="lottie-wrap">
          <div class="lottie">
            <lottie-player
              id="firstLottie"
              class="lot"
              :class="{ hide: active2 }"
              style="width: 300px"
              src="https://assets2.lottiefiles.com/packages/lf20_wjj7ygly.json"
            ></lottie-player>
            <lottie-player
              id="secondLottie"
              class="lot"
              :class="{ show: active2 }"
              style="width: 300px"
              autoplay
              loop
              src="https://assets2.lottiefiles.com/packages/lf20_wjj7ygly.json"
            ></lottie-player>
          </div>
          <div @mouseover="active3 = true" @mouseleave="active3 = false">
            <a
              id="hover"
              @mouseover="active2 = true"
              @mouseleave="active2 = false"
              class="submit-btn"
              href=""
              >Submit your idea</a
            >
          </div>
        </div>
      </div>
    </LocomotiveScroll>
  </div>
</template>
<style scoped>
.approach-wrap {
  position: relative;
  /* color: white; */
}
.--offPurple {
  overflow: hidden;
  position: relative;
  color: rgba(10, 8, 59, 0.9);
  background-color: #e5eff8;
}
.wrap {
  max-width: 100ch;
}
.wrap-idea {
  max-width: 100ch;
  background: #05054b;
  border-radius: 20px;
  display: grid;
  justify-content: center;
  text-align: center;
  color: white;
}
.card img {
  margin: auto;
  max-width: 190px;
}
.cards {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
}
.card {
  border-radius: 20px;
  z-index: 4;
  background-color: #fff;
  flex: 30.33%;
  text-align: center;
}
.projects__list {
  --spacing: 60%;
  -webkit-padding-start: 0;
  align-items: start;
  display: grid;
  gap: calc(var(--step-5) * 1.25);
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  justify-items: center;
  list-style-type: none;
  margin: 0 auto;
  max-width: 1100px;
  padding-inline-start: 0;
}
.project__image__wrapper {
  aspect-ratio: 1/1;
  height: unset;
  max-height: unset;
  min-height: unset;
}

.project__image__wrapper {
  height: 40vw;
  max-height: 30rem;
  min-height: 20rem;
  overflow: hidden;
  width: 100%;
}
.project__image {
  display: block;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
  -o-object-position: center center;
  object-position: center center;
  width: 100%;
}
.project__wrapper {
  cursor: none;
  display: grid;
  grid-template-rows: -webkit-fit-content -webkit-fit-content;
  grid-template-rows: fit-content fit-content;
  text-decoration: none;
}
.cards p {
  max-width: 30ch;
  font-size: 1rem;
}
.--offPurple .rightSymbol2 {
  position: absolute;
  z-index: 0;
  top: 0;
  right: 0;
  z-index: 0;
  pointer-events: none;
  width: 394.59px;
  height: 503.63px;
}
h4 {
  font-weight: 600;
  font-size: 1.4rem;
}
h3 {
  font-weight: 600;
}
.lottie {
  margin-top: -4rem;
}
svg {
  width: 100%;
  height: auto;
}
.--pink {
  color: #4181c5;
}
.--blur {
  filter: blur(90px);
}
img {
  border-radius: 10px;
}
.half picture {
  aspect-ratio: auto 485 / 589;
}
.col12 .half:before {
  background-position: right bottom;
  background-repeat: no-repeat;
  background-image: url('/img/download.svg');
}
@media only screen and (min-width: 768px) {
  .col12 .half {
    margin-bottom: 0;
  }
}
.col12 {
  max-width: 24rem;
  position: relative;
}
.col12 .half {
  position: relative;
  z-index: 1;
}
.col12.half {
  width: calc(100% - 24px);
  margin-bottom: 72px;
}

.col12 .half:before {
  border-radius: 10px;
  position: absolute;
  top: 0;
  left: 0;
  top: 24px;
  left: 24px;
  right: -24px;
  bottom: -24px;
  content: '';
  background-color: #05054b;
  z-index: -1;
}
.submit-btn {
  padding: 10px 40px;
  border-radius: 7px;
  color: #fff;
  background: #004990;
  border: solid 2px #004990;
  padding: 8px 30px;
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
.color {
  color: black;
}
.hovered {
  background: #dfebf8;
  color: #05054b;
  transition: background 1s ease-in-out;
}
</style>
<script>
export default {
  // mounted() {
  //   this.lmS = new this.locomotiveScroll({
  //     el: document.querySelector('#js-scroll'),
  //     smooth: true,
  //   })
  //   console.log('lmS', this.lmS)
  // },
  async asyncData({ $content }) {
    const page = await $content('index').fetch()
    const posts = await $content('blog').fetch()

    return {
      page,
      posts,
    }
  },
  data() {
    return {
      active2: false,
      active3: false,
      // lmS: null,
    }
  },
}
</script>
