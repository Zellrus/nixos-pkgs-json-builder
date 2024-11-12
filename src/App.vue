<template>
  <Header />
  <main>
    <RouterView/>
  </main>
  <Footer/>
</template>

<script>
import Header from "@/components/Header.vue"
import Footer from "@/components/Footer.vue"
export default{
  components :{
    Header,
    Footer,
  }
}
</script>

<style scoped>
main{
  background-image: linear-gradient(315deg, #002244, #3457D5);
  flex: 1;

}
</style>
