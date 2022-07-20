<template>
  <div>
    <div class="hero-manifesto">
      <div class="heading-wrapper">
        <div class="wrap-head">
          <div>
            <h1 class="heading">Manifesto</h1>
          </div>
          <h1 class="shadow-heading">MANIFESTO</h1>
          <p class="paragraph-hero">
            We use technology to make things better for customers, simpler for
            colleagues and more efficient for boots
          </p>
        </div>
      </div>
    </div>
    <div class="points">
      <div class="numbers-wrap">
        <div>
          <h1>01</h1>
        </div>
        <div class="text-wrap">
          <p>
            We prioritise the biggest opportunities and pursue them with
            technology solutions
          </p>
        </div>
      </div>
      <div class="numbers-wrap">
        <div>
          <h1>02</h1>
        </div>
        <div class="text-wrap">
          <p>
            We're entrepreneurially curious, finding and incubating new ideas
            rapidly
          </p>
        </div>
      </div>
      <div class="numbers-wrap">
        <div>
          <h1>03</h1>
        </div>
        <div class="text-wrap">
          <p>We're agnostic and trusted with new and emerging technologies</p>
        </div>
      </div>
      <div class="numbers-wrap">
        <div>
          <h1>04</h1>
        </div>
        <div class="text-wrap">
          <p>We focus on outcomes</p>
        </div>
      </div>
      <div class="numbers-wrap">
        <div>
          <h1>05</h1>
        </div>
        <div class="text-wrap">
          <p>We are open and collaborative - taking others to the journey</p>
        </div>
      </div>
      <div class="numbers-wrap">
        <div>
          <h1>06</h1>
        </div>
        <div class="text-wrap">
          <p>We are open and collaborative - taking others to the journey</p>
        </div>
      </div>
      <div class="numbers-wrap">
        <div>
          <h1>07</h1>
        </div>
        <div class="text-wrap">
          <p>
            We're driven by innovation, we connect, share and work with anyone
            who can help get things done
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.numbers-wrap {
  display: flex;
  gap: 2rem;
  margin-bottom: 2rem;
}
.hero-manifesto {
  padding-top: 8rem;
  padding-bottom: 4rem;
  color: #20325a;
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
  margin-left: 13rem;
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
.points h1 {
  font-size: 2.8rem;
  font-weight: 800;
}
.text-wrap {
  align-self: center;
}
.points {
  padding: 2rem 2rem 2rem 6rem;
  background: transparent linear-gradient(136deg, #20325a 0%, #3d619b 100%) 0%
    0% no-repeat padding-box;
  color: white;
}
</style>
