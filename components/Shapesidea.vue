<template>
  <section class="background anim--hero2">
    <svg
      role="presentation"
      class="anim-header2 anim-header--conf"
      preserveAspectRatio="xMidYMid slice"
      viewBox="0 0 1440 902.88"
    >
      <g opacity="0" ref="fouc2" class="fouc2">
        <g class="hero-shape-subtle">
          <path
            d="M935,594.2c-26.26-160,82.15-311,242.13-337.24s311,82.15,337.24,242.13l96.56-15.85c-35-213.31-236.33-357.85-449.65-322.84S803.39,396.73,838.4,610Z"
            fill="#4899df"
          />
          <path
            d="M1128.08,562.49a97.85,97.85,0,0,1,193.12-31.7l96.57-15.85C1400.26,408.29,1299.6,336,1192.94,353.52S1014,471.69,1031.52,578.34Z"
            fill="#4899df"
          />
        </g>
        <circle
          class="hero-shape2"
          cx="140"
          cy="66"
          r="105"
          fill="#c7dbf4"
          opacity="0.2"
        />
        <path
          class="hero-shape2"
          d="M183.56,330.78A12,12,0,0,1,196.81,326l72.36,20.75a12,12,0,0,1,8.68,11.12L280.48,433a12,12,0,0,1-7.89,11.69l-70.73,25.75a12,12,0,0,1-13.56-3.89L142,407.28a12,12,0,0,1-.49-14.1Z"
          fill="#205bad"
        />
        <path
          class="hero-shape2"
          d="M740.93,335.64a6,6,0,0,1-7.91,2.88l-19.61-9.14a6,6,0,1,1,5-10.8l6.57,3.06-8.11-22.28a6,6,0,0,1,11.19-4.07l8.11,22.28,3.06-6.57a6,6,0,1,1,10.8,5Z"
          fill="#205bad"
          fill-rule="evenodd"
        />
        <circle class="hero-shape" cx="804" cy="191" r="10" fill="#c7dbf4" />
        <circle
          class="hero-shape2"
          data-name="dot"
          cx="34"
          cy="374"
          r="10"
          fill="#4899df"
        />
        <path
          class="hero-shape2"
          d="M165.93,776.09a28.69,28.69,0,1,0,49.15,29.61l30,18.09A63.76,63.76,0,1,1,135.89,758Z"
          fill="#00c0cc"
          fill-rule="evenodd"
        />
      </g>
    </svg>
  </section>
</template>

<script>
import { gsap } from 'gsap'
import { ScrollTrigger } from 'gsap/ScrollTrigger'
import { MotionPathPlugin } from 'gsap/MotionPathPlugin'
gsap.registerPlugin(MotionPathPlugin, ScrollTrigger)
export default {
  mounted() {
    this.moonDown()
    ScrollTrigger.refresh(true)
  },
  methods: {
    moonDown() {
      const tl3 = gsap.timeline({
        scrollTrigger: {
          trigger: '.anim-header2',
          start: 'top 40%',
          end: 'bottom top',
          toggleActions: 'play pause restart reset',
        },
      })
      tl3
        .to('.fouc2', { duration: 1, delay: 0.4 })
        .to(
          '.stroke',
          {
            drawSVG: '0%',
            duration: 6,
            ease: 'power2.out',
            opacity: 0.3,
          },
          1
        )
        .to(
          '.hero-shape2',
          {
            transformOrigin: 'center',
            rotate: 'random(80, -80)',
            x: 'random([-150, -100, -200, 200, 100, 150])',
            y: 'random([-150, -100, -200, 200, 100, 150])',
            ease: 'expo.out',
            duration: 6,
          },
          '=-6'
        )
    },
  },
}
</script>

<style scoped>
.anim-header2 {
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  width: 100vw;
  min-width: 800px;
  z-index: 0;
  overflow: visible;
}
.fouc2 {
  opacity: 0.5;
}
</style>
