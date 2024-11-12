<template>
  <nav>
    <NavButton></NavButton>
    <NavButton></NavButton>
    <NavButton></NavButton>
    <NavButton></NavButton>
    <NavButton></NavButton>
  </nav>
</template>

<script>
import NavButton from '@/components/NavButton.vue'
export default{
  components:{
    NavButton,
  }
}
</script>

<style scoped>
nav{
  height: 100%;
  background: rgb(37, 59, 86);
  display: flex;
  gap: 10px;
  padding: 10px;
}
a{
  all:unset;
  color:grey;
}
</style>