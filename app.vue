<template>
  <div id="app">
 
    <Index/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Index from './view/index.vue';

@Component({
  components: {
    Index,
  },
})
export default class App extends Vue {
  mounted(){
    
  }
}
</script>

<style>
#app {

}
</style>
