<template>
  <div class="flex justify-center h-hero hero">
    <section
      class="hero --purple --padTop1 --padBottom1 heroHome effect--ready"
      data-waypoint="waypoint"
    >
      <!-- <div class="leftSymbol symbol --green --blur">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="currentColor"
          viewBox="0 0 531 595"
        >
          <g id="cSymbol">
            <path
              fill="currentColor"
              d="M423.549 233.293c-6.486 1.761-13.116-1.733-16.108-8.184-30.435-65.727-99.943-102.167-168.648-83.518-79.446 21.566-127.687 108.673-107.73 194.525 17.245 74.269 79.79 123.281 147.761 121.233 6.673-.197 12.654 4.469 14.282 11.481l24.266 104.503c2.053 8.843-3.533 17.789-11.926 18.809C170.838 608.599 42.431 515.298 8.541 369.35-28.36 210.335 60.96 49.055 208.036 9.131 343.008-27.507 479.78 50.754 529.901 186.788c3.133 8.478-1.523 18.026-9.703 20.247l-96.649 26.258Z"
            ></path>
          </g>
        </svg>
      </div> -->

      <!-- <div class="rightSymbol1 symbol --pink --blur">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="currentColor"
          class="full"
          viewBox="0 0 531 595"
        >
          <use xlink:href="#cSymbol"></use>
        </svg>
      </div> -->
      <!-- <div class="rightSymbol2 symbol">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="currentColor"
          viewBox="0 0 531 595"
        >
          <use xlink:href="#cSymbol"></use>
        </svg>
      </div> -->
    </section>
    <img :src="image" class="object-cover w-screen" />
    <div class="absolute">
      <div class="justify-center h-hero">
        <h2 class="py-4" v-if="heading">
          {{ heading }}
        </h2>
        <h3
          style="z-index: 2"
          v-if="subheading"
          class="px-4 text-lg text-white sm:text-xl md:text-2xl"
        >
          {{ subheading }}
        </h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    heading: {
      type: String,
      default: null,
    },
    subheading: {
      type: String,
      default: null,
    },
    image: {
      type: String,
      required: true,
    },
  },
}
</script>

<style scoped>
.h-hero {
  max-height: 25vw;
  display: grid;
  place-items: center;
  text-align: center;
}
.gradient-bg {
  position: absolute;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: -1;
  overflow: hidden;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  opacity: 0.5;
  -webkit-filter: blur(200px);
  filter: blur(200px);
}
.bg-circle._1 {
  width: 40vw;
  height: 40vw;
  margin-top: -16%;
  margin-left: -16%;
  border-radius: 20%;
  background-color: #7056f5;
  opacity: 1;
}

.hero {
  min-height: 60vh;
  color: #fff;
  background-color: #05054b;
  /* background: linear-gradient(180deg, #004990 0%, #004990 56.14%); */
}
.hero.--purple {
  color: #fff;
  color: var(--color-fill-brand-white);
  background-color: #5558af;
  background-color: var(--color-fill-brand-purple);
  background: linear-gradient(180deg, #556daf 0%, #004990 56.14%);
}
.hero.--purple .leftSymbol {
  display: block;
  top: 104px;
  left: -50px;
  width: 307.43px;
  height: 392px;
}

.hero.--purple .leftSymbol {
  display: block;
  top: 104px;
  left: -50px;
  width: 307.43px;
  height: 392px;
}
.hero .leftSymbol,
.hero .bottomSymbol2 {
  display: none;
}
.hero .symbol {
  position: absolute;
  z-index: 1;
  pointer-events: none;
  transform: translateZ(0);
  will-change: transform;
}
.hero .leftSymbol,
.hero .bottomSymbol2 {
  display: none;
}
.hero .symbol {
  position: absolute;
  z-index: 1;
  pointer-events: none;
  transform: translateZ(0);
  will-change: transform;
}
.--green {
  color: #41d3af;
  color: var(--color-fill-brand-green);
}
.--blur {
  filter: blur(90px);
}
.hero.--purple .rightSymbol1,
.hero.--purple .rightSymbol2 {
  right: -131px;
  top: 146px;
  width: 307.43px;
  height: 392.38px;
}

.hero.--purple .rightSymbol1 {
  z-index: 3;
}
.hero.--purple .rightSymbol1,
.hero.--purple .rightSymbol2 {
  right: -131px;
  top: 146px;
  width: 307.43px;
  height: 392.38px;
}
.hero .rightSymbol1,
.hero .rightSymbol2 {
  right: -301px;
  top: -76px;
  width: 456.27px;
  height: 582.35px;
}
.hero .symbol {
  position: absolute;
  z-index: 1;
  pointer-events: none;
  transform: translateZ(0);
  will-change: transform;
}
.hero .rightSymbol1,
.hero .rightSymbol2 {
  right: -301px;
  top: -76px;
  width: 456.27px;
  height: 582.35px;
}
.hero .symbol {
  position: absolute;
  z-index: 1;
  pointer-events: none;
  transform: translateZ(0);
  will-change: transform;
}
.--pink {
  color: #cb9acd79;
  color: var(--color-fill-brand-pink);
}
.--blur {
  filter: blur(90px);
}
h3 {
  max-width: 60ch;
}
h2 {
  font-size: 2.5rem;
  font-weight: 600;
}
</style>
