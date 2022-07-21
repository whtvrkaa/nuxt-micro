<template>
  <section>
    <Pointer />
    <Form />
  </section>
</template>

<style scoped>
.hero-manifesto {
  padding-top: 5rem;
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
.wrap-team {
  width: 100vw;
  background-color: #dfebf8;
}
.avatar {
  z-index: 2;
}
.heading {
  margin-left: 4.5rem;
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
.contained {
  max-width: 1180px !important;
  margin: 0 auto !important;
}
section {
  display: grid;
  justify-content: center;
}
@media (min-width: 768px) {
  #people figure {
    min-width: 30% !important;
    max-width: 30% !important;
  }
}

.ring {
  position: absolute;
  z-index: 0;
  width: 9rem !important;
  height: 9rem !important;
  margin-left: -0.6rem;
  margin-top: 9rem;
}
#wrap-h {
  max-width: 900px !important;
  /* max-height: 1750px !important; */
  margin: 0 auto;
  display: flex;
}
.vl {
  border-left: 10px solid #20325a;
  height: 90px;
  padding-right: 1rem;
  align-self: center;
}
#wrap-h p {
  color: #7f8896;
}
h2 {
  font-size: 2.4rem;
}
section {
  padding: 2rem;
}
#people {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
#people figure img {
  border-radius: 100%;
  margin-bottom: 20px;
  height: 125px;
  width: 125px;
  align-self: center;
}
#people p {
  color: #323335;
}
#people figure h3 {
  font-size: 1.3rem;
  font-weight: 700;
  color: #00539f;
}
/* #people figcaption {
  align-self: center !important ;
} */

#people figure {
  display: flex;
  flex-direction: column;
  text-align: center;
  padding: 20px 0px;
  padding-right: 40px;
}
.avatar-wrap {
  position: relative;
  display: grid;
  justify-content: center;
}
.ring-wrap {
  display: grid;
  justify-content: center;
}
</style>
