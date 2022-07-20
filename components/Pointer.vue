<template>
  <div class="cursor-preview">
    <div class="custom-cursor">
      <div id="cursor-big" class="custom-cursor__ball custom-cursor__ball--big">
        <img
          style="padding: 0.4rem"
          id="icon"
          class="icon"
          src="img/arrow-link.svg"
          alt=""
        />
      </div>
      <div
        id="cursor-small"
        class="custom-cursor__ball custom-cursor__ball--small"
      ></div>
    </div>
  </div>
</template>

<script>
import gsap from 'gsap'
export default {
  mounted() {
    const cursorBig = document.getElementById('cursor-big')
    const cursorSmall = document.getElementById('cursor-small')
    const icon = document.getElementById('icon')
    const links = document.getElementsByClassName('hoverable')
    const links2 = document.getElementsByClassName('hoverable-link')
    const withClassHover = document.getElementsByClassName('cursor-hover')
    const withClassHover2 = document.getElementsByClassName('cursor-hover2')
    const withHover = [...links, ...withClassHover]
    const withHover2 = [...links2, ...withClassHover2]

    // Event Listeners
    document.addEventListener('mousemove', onMouseMove)
    document.addEventListener('mousedown', onMouseHover)
    document.addEventListener('mouseup', onMouseHoverOut)
    document.addEventListener('mouseenter', () => {
      cursorBig.style.opacity = 1
      cursorSmall.style.opacity = 1
    })
    document.addEventListener('mouseleave', () => {
      cursorBig.style.opacity = 0
      cursorSmall.style.opacity = 0
    })
    withHover.forEach((element) => {
      element.addEventListener('mouseover', onMouseHover)
      element.addEventListener('mouseout', onMouseHoverOut)
    })
    withHover2.forEach((element) => {
      element.addEventListener('mouseover', onMouseHover2)
      element.addEventListener('mouseout', onMouseHoverOut2)
    })
    // Event Handlers
    function onMouseMove(e) {
      cursorSmall.style.opacity = 1
      gsap.to(cursorBig, 0.4, {
        x: e.clientX - 8,
        y: e.clientY - 8,
      })
      gsap.to(cursorSmall, 0.1, {
        x: e.clientX - 4,
        y: e.clientY - 4,
      })
    }
    function onMouseHover() {
      gsap.to(cursorBig, 0.3, {
        scale: 4,
      })
      gsap.to(icon, { opacity: 1 })
    }
    function onMouseHoverOut() {
      gsap.to(cursorBig, 0.3, {
        scale: 1,
      })
      gsap.to(icon, { opacity: 0 })
    }
    function onMouseHover2() {
      gsap.to(cursorBig, 0.3, {
        scale: 4,
      })
    }
    function onMouseHoverOut2() {
      gsap.to(cursorBig, 0.3, {
        scale: 1,
      })
      gsap.to(icon, { opacity: 0 })
    }
  },
}
</script>

<style>
.cursor-preview__title {
  /* font-size: 18px; */
  line-height: 24px;
  color: #8a9eff;
  margin-bottom: 5px;
}

.cursor-preview__link {
  color: #fff;
  font-weight: 600;
  /* font-size: 18px; */
  line-height: 29px;
}
.icon {
  opacity: 0;
}
.custom-cursor__ball {
  mix-blend-mode: difference;
  background: white !important;
  content: '';
  position: fixed;
  top: 0;
  left: 0;
  z-index: 99999;
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.5s ease;
}

.custom-cursor__ball--big {
  content: '';
  width: 20px;
  height: 20px;
  /* background-image: url('https://img.icons8.com/ios/2x/cursor.png') !important; */
  background-size: cover;
  background: #29217a;
  border-radius: 50%;
}
/* .custom-cursor__ball {
  background-image: url('https://img.icons8.com/ios/2x/cursor.png') !important;
  background-size: cover;
} */
/* .custom-cursor__ball--small {
  content: '';
  width: 6px;
  height: 6px;
  background: #78fff1;
  border-radius: 50%;
} */
</style>
