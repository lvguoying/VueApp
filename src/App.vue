<template>
  <div id="app">
    <common-header></common-header>
    <router-view/>
    <common-footer></common-footer>
  </div>
</template>

<script>
import CommonHeader from '@/components/common/Header'
import CommonFooter from '@/components/common/Footer'
export default {
  name: 'App',
  components:{
     CommonHeader,
     CommonFooter
  }
}
</script>

<style>

</style>
