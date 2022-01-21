<template>
  <div id="app">{{ text }}</div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import { parse, PropDescriptor } from 'vue-docgen-api'

@Component
export default class App extends Vue {
  text: string = 'Hello World'
}
</script>

<style lang="scss">
html,
body,
#app {
  width: 100%;
  height: 100%;
}
</style>
