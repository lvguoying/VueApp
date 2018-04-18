<template>
    <div>
        <Common-header bgColor="rgb(0,150,136)">
            <span slot="title">Music</span>
        </Common-header> 
          <h1>movie</h1>
        <Common-footer bgColor="rgb(0,150,136)"></Common-footer>
    </div>
</template>
<script>
import CommonHeader from "@/components/common/Header";
import CommonFooter from "@/components/common/Footer";
export default {
  components: {
    CommonHeader,
    CommonFooter
  }
};
</script>

<style scoped>

</style>
