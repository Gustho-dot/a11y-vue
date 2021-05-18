<template>
  <div class="content-wrapper">
   <text-section rubrik="Rubrik 1" image="computer.png" />
   <text-section rubrik="Rubrik 2" image="eagle.png" />
   <text-section rubrik="Rubrik 3" image="tree.png" />
  </div>
</template>

<script>
import TextSection from '../components/TextSection.vue'
// @ is an alias to /src


export default {
  name: 'Home',
  components: {
    TextSection
   
  }
}
</script>
