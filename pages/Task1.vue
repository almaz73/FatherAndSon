<template>
    <div>
      <h2>Квадрат посередине экрана</h2>
      <div class="my-area">
        <div class="rectangle_1"></div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "task1"
    }
</script>

<style scoped>
  h2{
    top: 20px;
    text-align: center;
  }
.my-area{
  width: 100%;
  height: 100%;
  position: fixed;
  display: flex;
  align-items: center;
  justify-content: center;
}
  .rectangle_1{
    background: red;
    width: 100px;
    height: 100px;
  }
</style>
