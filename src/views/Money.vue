<template>
    <div class="nav">
      <div class="content">
        <p>Money</p>
        <p>Money</p>
      </div>
      <Nav/>
    </div>
</template>

<script>
export default {
name: "Money"
}
</script>

<style lang="scss" scoped>
  .nav{
    display: flex;
    flex-direction: column;
    border: 1px solid red;
    height: 100vh;

  }
  .content{
    overflow: auto;
    flex-grow: 1;
    border: 1px solid blue;
  }
</style>