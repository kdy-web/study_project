<template>
  <el-container>
  
  <el-main>
  <div class="index-top-box">
  <div class="index-top">
  </div>
  </div>
   
  
  </el-main>
</el-container>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

   .el-container,.el-main {
   	padding: 0;
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
     
  }
  .index-top-box{
  	height: 3.06rem;
  	background-image: linear-gradient(-180deg, #2B94FA 43%, #55BFE2 100%);
  }
  .index-top{
  	height: 0.48rem;
  }
</style>
