<template>
  <div class="container">
    <img class="responsiveLogo" src="../assets/LauchLogoTrimmed2.png"/>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class HelloWorld extends Vue {
  ScrollNext () {
    alert('hello')
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .container {
        display: flex;
        justify-content: center;
        align-items: center;
        overflow: hidden;
    }
    .responsiveLogo {
        max-width: 55%;
        height: auto;
    }
</style>
