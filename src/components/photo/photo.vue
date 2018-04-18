<template>
    <div>
        <Common-header bgColor="rgb(121,255,72)">
            <span slot="title">Photo</span>
        </Common-header> 
          <h1>movie</h1>
        <Common-footer bgColor="rgb(121,255,72)"></Common-footer>
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
