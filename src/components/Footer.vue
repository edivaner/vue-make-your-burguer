<template>
  <div>
    <footer>
        <p>Make Your burger &copy; 2022</p>
    </footer>
  </div>
</template>


<script>
export default {
    name:"FooterComponent"
}
</script>

<style scoped>
  footer{
    height: 200px;
    background-color: #222;
    border-top: 4px solid #111;
    color: #FCBA03;
    display: flex;
    align-items: center;
    justify-content: center;
    bottom: 0;
    width: 100%;
  }
</style>