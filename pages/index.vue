<template>
  <div :style="image">
    <NuxtLink to="/about">
      About
    </NuxtLink>
    <NuxtLink to="/projects">
      Projects
    </NuxtLink>
  </div>
</template>

<script>
import background from 'assets/background.svg'
export default {
  data () {
    return {
      image: { backgroundImage: `url(${background})` }
    }
  }
}
</script>
