<template>
  <div>
    <div>Blacksquadron</div>
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
  h2 {
    top: 20px;
    text-align: center;
  }

  .New-area {
    width: 100%;
    height: 100%;
    position: fixed;
    display: flex;
    align-items: end;
    justify-content: center;
  }

  .blackrectangle {
    background: black;
    width: 100px;
    height: 100px;
  }
</style>
