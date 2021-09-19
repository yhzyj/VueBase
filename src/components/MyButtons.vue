<template>
 <div>
   <h2>我爱赵丽颖</h2>
   <button @click="count++">爱了{{count}}次</button>
 </div>
</template>

<script>
export default {
  name: "",
  data() {
    // 组件当中的this就是当前组件
    return {
      count:0
    }
  }
}
</script>

<style scoped>
  h2 {
  color: pink;
}
</style>