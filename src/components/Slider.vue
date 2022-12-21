<template>
  <Vue3Marquee>
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/SyFSngZ/g3.jpg" />
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/w6y173n/dell.jpg" />
    <img class="px-8" height="200" width="300" src="https://i.ibb.co/RD2Gt2k/zen.jpg" />
  </Vue3Marquee>
</template>

<script>
import { Vue3Marquee } from 'vue3-marquee'
import 'vue3-marquee/dist/style.css'

export default {
  components: {
    Vue3Marquee,
  },
}
</script>