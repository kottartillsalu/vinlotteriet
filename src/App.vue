<template>
  <v-app>
    <HelloWorld/>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      title: 'Vinlotteriet'
    }
  }
}
</script>
