<template>
  <div class="header" :style="{background:bgColor}">
    <span class="home" @click="$emit('home',{bgColor:'rgb(33,150,243)',title:'Movie'})">首页</span>
    <h2 class="title">
      <slot name="title">默认值</slot>
    </h2>
  </div>
</template>

<script>
export default {
   props:['bgColor']
}
</script>
 
<style scoped>
.header{
  height: 1rem;
  /* background-color: rgb(33,150,243); */
  color: #ffffff;
  line-height: 1rem;
  position: fixed;
  top: 0;
  width: 100%;
}
.title{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
  color: #ffffff;
  /* background-color: rgb(33,150,243); */
}
.home{
  color: #ffffff;
  /* background-color: rgb(33,150,243); */
  margin-left: .1rem;  
}
</style>