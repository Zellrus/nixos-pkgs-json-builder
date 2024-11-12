<template>
   <RouterLink to="/">
    <div class="container">
      <div class="icon">
          <svg  viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M14 21.0001V15.0001H10V21.0001M19 9.77818V16.2001C19 17.8802 19 18.7203 18.673 19.362C18.3854 19.9265 17.9265 20.3855 17.362 20.6731C16.7202 21.0001 15.8802 21.0001 14.2 21.0001H9.8C8.11984 21.0001 7.27976 21.0001 6.63803 20.6731C6.07354 20.3855 5.6146 19.9265 5.32698 19.362C5 18.7203 5 17.8802 5 16.2001V9.77753M21 12.0001L15.5668 5.96405C14.3311 4.59129 13.7133 3.9049 12.9856 3.65151C12.3466 3.42894 11.651 3.42899 11.0119 3.65165C10.2843 3.90516 9.66661 4.59163 8.43114 5.96458L3 12.0001" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
      </div>
      <p>
        Home
      </p>
  </div>
</RouterLink>
</template>

<script>

</script>

<style scoped>
.icon{
  width: 25px;
  height: 25px;
  align-self: center;
}
.container{
  display: flex;
  flex-direction: column;
  text-align: center;
  padding: 5px;
  background-color: rgb(24, 51, 69);
  border-radius: 10px;
}
p{
  all:unset;
}
</style>