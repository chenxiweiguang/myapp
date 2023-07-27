<template>
  <div class="d-flex bd-highlight" style="background-color: #17c4ff;">
  <div class="p-2 flex-fill bd-highlight">
    <div class="p-2 bd-highlight"><Chart1></Chart1></div>
  <div class="p-2 bd-highlight"><Chart2></Chart2></div>
  </div>
  <div class="p-2 flex-fill bd-highlight"><China></China></div>
  <div class="p-2 flex-fill bd-highlight">
    <div class="p-2 bd-highlight"><Chart3></Chart3></div>
  <div class="p-2 bd-highlight"><Chart4></Chart4></div>
    </div>
</div>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <!-- <HelloWorld msg="Hello Vue 3.0 + Vite" /> -->
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Chart1 from './components/Chart1.vue'
import Chart2 from './components/Chart2.vue'
import Chart3 from './components/Chart3.vue'
import Chart4 from './components/Chart4.vue'
import Maps from './components/Maps.vue'
import China from './components/China.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    Chart1,
    Chart2,
    Chart3,
    Chart4,
    Maps,
    China
  }
}
</script>
