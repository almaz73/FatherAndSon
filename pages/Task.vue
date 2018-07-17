<template>
  <div>
    <div>Blacksquadron</div>
    <div class="Orange">
      <div class="orangerectangle1"></div>
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

  .Orange {
    width: 100%;
    height: 100%;
    position: fixed;
    display: flex;
    align-items: end;
    justify-content: center;
  }

  .orangerectangle1 {
    background:orangered;
    width: 100px;
    height: 100px;
  }
</style>
