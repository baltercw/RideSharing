<template>
  <div class="logo-moving-part">
    <!-- BooJo 跑馬燈 -->
    <div class="marquee-wrapper">
      <div class="marquee-text">
        <div class="marquee-inner">
          <span>BooJo • BooJo • BooJo • BooJo • BooJo •</span>
          <span>BooJo • BooJo • BooJo • BooJo • BooJo •</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted, defineProps, defineEmits } from 'vue'
import { gsap } from 'gsap'
import logoUrl from '@/assets/pik.png'

const props = defineProps({
  initialImagePosition: {
    type: Object,
    default: () => ({ x: 300, y: 400 })
  }
})

const emit = defineEmits(['update-image-position'])
const imageA = ref(null)
const currentPosition = ref(props.initialImagePosition)

onMounted(() => {
  if (!imageA.value) return

  gsap.set(imageA.value, {
    x: currentPosition.value.x,
    y: currentPosition.value.y
  })

  const observer = new IntersectionObserver((entries) => {
    if (entries[0].isIntersecting) {
      animateImage()
    }
  }, { threshold: 0.5 })

  observer.observe(document.querySelector('.logo-moving-part'))
  return () => observer.disconnect()
})

const animateImage = () => {
  const targetPosition = { x: 300, y: 400 }
  gsap.to(currentPosition.value, {
    x: targetPosition.x,
    y: targetPosition.y,
    duration: 1,
    ease: "power2.out",
    onUpdate: () => {
      emit('update-image-position', { ...currentPosition.value })
    }
  })
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Unbounded:wght@700&display=swap');

.logo-moving-part {
  background-color: transparent;
  width: 100%;
  height: 100vh;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

/* 跑馬燈外層裁切 */
.marquee-wrapper {
  width: 100%;
  overflow: hidden;
}

/* 滑動本體 */
.marquee-text {
  display: inline-block;
  white-space: nowrap;
  animation: marquee 50s linear infinite;
}

/* 發光 + 跳動：作用在內層 */
.marquee-inner {
  display: inline-block;
  font-family: 'Unbounded', sans-serif;
  font-size: 10rem;
  color: rgba(209, 173, 68, 0.5);
  text-shadow:
    0 0 8px rgba(209, 173, 68, 0.5),
    0 0 20px rgba(209, 173, 68, 0.4),
    0 0 30px rgba(209, 173, 68, 0.3);
  animation: pulse 2.5s ease-in-out infinite;
}

.marquee-inner span {
  display: inline-block;
  padding-right: 4rem;
}

@keyframes marquee {
  0%   { transform: translateX(0%); }
  100% { transform: translateX(-50%); }
}

@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50%      { transform: scale(1.02); }
}

/* logo 圖片動畫 */
.image-a {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 3;
}
.image-a img {
  width: 100px;
  height: 100px;
  object-fit: contain;
}
</style>