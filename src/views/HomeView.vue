<template>
    <div class="container">
    <div class="header">
        <div>
            ThunderCoin
        </div>
        <div>
            Настройки
        </div>
    </div>
<div class="main">
    <p>Баланс</p>
    10000

    <progress value="10" max="100">70 %</progress>
</div>
</div>
</template>

<script>

</script>
<style scoped>
.header{
display: flex;
justify-content: space-between;
padding: 5px 15px;
}
.container{
display: flex;
flex-direction: column;
}
.main{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 10px
}
progress {
    all:unset;
  width: 100%;
  height: 22px;
  border-radius: 50px;
}
progress::-webkit-progress-bar {
    all:unset;
  height: 22px;
  background-color: black;
  border-radius: 50px;
}
progress::-webkit-progress-value {
    background-color: blue;
    border-radius: 50px;
}
progress::-webkit-progress-inner-element{
    border-radius: 50px;
    background-color: gray;
}
</style>