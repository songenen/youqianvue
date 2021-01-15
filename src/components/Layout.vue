<template>
  <div class="nav">
    <div class="content">
      <slot/>
    </div>
    <Nav/>
  </div>
</template>

<script>
export default {
name: "Layout"
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