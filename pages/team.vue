<template>
  <section>
    <Pointer />
    <div class="hero-manifesto">
      <div class="heading-wrapper">
        <div class="wrap-head">
          <div>
            <h1 class="heading">Our Team</h1>
          </div>
          <h1 class="shadow-heading">TEAM</h1>
          <p style="padding-bottom: 3rem" class="paragraph-hero">
            Here is our amazing team
          </p>
        </div>
      </div>
      <div class="wrap-team">
        <section id="people" style="padding-top: 5rem">
          <figure>
            <div class="avatar-wrap">
              <div class="ring-wrap">
                <img class="ring" src="img/Circle_Blue.svg" alt="" />
              </div>
              <img
                style="z-index: 2"
                alt=""
                src="https://secure.gravatar.com/avatar/9c7aa6fd2c6aed29eb491135c775deba?s=100&amp;d=mm&amp;r=g"
                srcset="
                  https://secure.gravatar.com/avatar/9c7aa6fd2c6aed29eb491135c775deba?s=200&amp;d=mm&amp;r=g 2x
                "
                class="avatar avatar-100 photo"
                height="100"
                width="100"
                loading="lazy"
              />
            </div>

            <figcaption>
              <h3>Adam Cohen-Rose</h3>
              <p>Engineering</p>
            </figcaption>
          </figure>
          <figure>
            <div class="avatar-wrap">
              <div class="ring-wrap">
                <img class="ring" src="img/Circle_Blue.svg" alt="" />
              </div>
              <img
                alt=""
                src="https://secure.gravatar.com/avatar/207b9aa773b83a4ec7740b06d72a7a84?s=100&amp;d=mm&amp;r=g"
                srcset="
                  https://secure.gravatar.com/avatar/207b9aa773b83a4ec7740b06d72a7a84?s=200&amp;d=mm&amp;r=g 2x
                "
                class="avatar avatar-100 photo"
                height="100"
                width="100"
                loading="lazy"
              />
            </div>

            <figcaption>
              <h3>Adrian Bracewell</h3>
              <p>Head of Engineering</p>
            </figcaption>
          </figure>
          <figure>
            <div class="avatar-wrap">
              <div class="ring-wrap">
                <img class="ring" src="img/Circle_Blue.svg" alt="" />
              </div>
              <img
                alt=""
                src="https://secure.gravatar.com/avatar/9e4a648cdcda0cd1664dcdc1f0e6371e?s=100&amp;d=mm&amp;r=g"
                srcset="
                  https://secure.gravatar.com/avatar/9e4a648cdcda0cd1664dcdc1f0e6371e?s=200&amp;d=mm&amp;r=g 2x
                "
                class="avatar avatar-100 photo"
                height="100"
                width="100"
                loading="lazy"
              />
            </div>
            <figcaption>
              <h3>Doug Wood</h3>
              <p>Product Management</p>
            </figcaption>
          </figure>
          <figure>
            <div class="avatar-wrap">
              <div class="ring-wrap">
                <img class="ring" src="img/Circle_Orange.svg" alt="" />
              </div>
              <img
                alt=""
                src="https://secure.gravatar.com/avatar/c0471992182d4eb8fedc358984140e95?s=100&amp;d=mm&amp;r=g"
                srcset="
                  https://secure.gravatar.com/avatar/c0471992182d4eb8fedc358984140e95?s=200&amp;d=mm&amp;r=g 2x
                "
                class="avatar avatar-100 photo"
                height="100"
                width="100"
                loading="lazy"
              />
            </div>

            <figcaption>
              <h3>Harry Betteridge</h3>
              <p>UX Design Lead</p>
            </figcaption>
          </figure>
          <figure>
            <div class="avatar-wrap">
              <div class="ring-wrap">
                <img class="ring" src="img/Circle_Orange.svg" alt="" />
              </div>
              <img
                alt=""
                src="https://secure.gravatar.com/avatar/12d93530e600d59294fa82d4f7edc5b2?s=100&amp;d=mm&amp;r=g"
                srcset="
                  https://secure.gravatar.com/avatar/12d93530e600d59294fa82d4f7edc5b2?s=200&amp;d=mm&amp;r=g 2x
                "
                class="avatar avatar-100 photo"
                height="100"
                width="100"
                loading="lazy"
              />
            </div>

            <figcaption>
              <h3>Jacob Holder</h3>
              <p>Technical Programme Management</p>
            </figcaption>
          </figure>
          <figure>
            <div class="avatar-wrap">
              <div class="ring-wrap">
                <img class="ring" src="img/Circle_Orange.svg" alt="" />
              </div>
              <img
                alt=""
                src="https://secure.gravatar.com/avatar/8241c28189246d41d677e6afbcc2c0a2?s=100&amp;d=mm&amp;r=g"
                srcset="
                  https://secure.gravatar.com/avatar/8241c28189246d41d677e6afbcc2c0a2?s=200&amp;d=mm&amp;r=g 2x
                "
                class="avatar avatar-100 photo"
                height="100"
                width="100"
                loading="lazy"
              />
            </div>

            <figcaption>
              <h3>James Salter</h3>
              <p>Engineering</p>
            </figcaption>
          </figure>
        </section>
      </div>
    </div>
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
