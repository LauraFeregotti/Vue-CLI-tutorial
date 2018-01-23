<template>
  <div>
    <h1>{{title}}</h1>
    <ninjas> </ninjas>

  </div>
</template>

<script>
import ninjas from './ninjas.vue'
export default {
 components:{
'ninjas':ninjas
 },
  data () {
    return {
      title:'Ninja App'
    }
  },

}
</script>

<style>

</style>
