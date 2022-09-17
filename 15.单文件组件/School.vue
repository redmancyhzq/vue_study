<template>
  <!-- 组件的结构 -->
   <div>
      <h2>学校名称： {{name}}</h2>
      <h2>学校地址： {{address}}</h2>
      <button @click="showX">点我输出X</button>
    </div>
</template>
<script>
export default {
  //组件交互相关的代码（数据，方法等）
  data(){
    return {
      name: '清华大学',
      address: 'beijing',
      x: 1,
    }
  },
  methods: {
    showX() {
      
    }
    
  },
}
</script>
<style scoped>
  /* 组件的样式 */
</style>