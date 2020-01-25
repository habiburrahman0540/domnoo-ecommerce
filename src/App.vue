<template>
  <div>
    <comp-Header/>
    <div>
      hello
    </div>
<comp-Footer/>
  </div>
</template>

<script>
import compHeader from './components/Header-Footer/Header.vue';
import compFooter from './components/Header-Footer/Footer.vue';
export default {
  components:{
    compHeader ,
    compFooter
  }
}
</script>
<style>
  @import './assets/style.css';
</style>