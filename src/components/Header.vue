<template>
  <div class="all">
    <div class="content">
      <h1>TODOLIST</h1>
    </div>
  </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
*{
  padding: 0;
  margin: 0;
}
  .content{
    width: 100%;
    height: 60px;
    background-color: #333;
  }
.content h1{
  color: #999;
  font-weight: bold;
  text-align: center;
  line-height: 60px;
}
</style>
