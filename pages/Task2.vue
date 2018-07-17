<template>
  <div class="root-div">
    <h4>попробуем без флекс</h4>
    обрати внимание на  height: 90vh; - что это означает? попробуй изменить <br>
    просто поиграйся, измени эти элементы, и сохрани
    <div class="New-area">
      <div class="blackrectangle"></div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "Task2"
  }
</script>

<style scoped>

  .root-div {
    text-align: center;
    background: yellow
  }

  .New-area {
    width: 100vw;
    height: 90vh;
  }

  .blackrectangle {
    margin: 100px auto;
    background: black;
    width: 100px;
    height: 100px;
  }
</style>
